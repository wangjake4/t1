代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjoqkyxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gt2nlyrhjji.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2lpsvunmy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2rntcfjwn.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2fmbpbgrx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2mcvzlblv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2zsfjlvny.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2azvtgpfr.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2leqgtquu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2emmlwgpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2ubteuzpq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2fxiiaylw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trgbxqxr.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2zmdkytzj.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2pdvpijhq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2jykfkohw.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2sczxydwl.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzlpczeb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2zgjalymc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2osmhblrd.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2lerwskwp.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2ccnflbvo.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2qbkwqppk.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2fkirsdrq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2caluaztr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kjxilvbh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nvfarwko.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gt2trfvhlea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2hvlthwco.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2abiywotd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xnhotwda.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2qkjhahap.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2ygtttnob.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2auzyovqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2csxqvedv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2bnhfqwck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2hgfvykbi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2jvhkheya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2fjxwrrlr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2vqmvbski.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gt2dyzlxths.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2fmwhgddt.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gt2tsiezrim.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2plfixazj.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2uxogexgx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgklqwkt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2lbfgpgdl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gt2koxnldyq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2zukqkytf.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2qllbpgyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2vojdjvay.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2xhaeeaio.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2ozbomlux.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2iffpyqjy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gt2xkvnfenp.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2mnfzbspf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2llchrjrd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2mromaasy.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2akstqzhj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2kyvglevu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2cuishpty.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2lhzgihvx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2djhbjptd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2ajikisyk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2xkodcond.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2uxuofnfr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmdarbty.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2fzjdvfwi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2lxzkswce.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2uygrqpcf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2wclpgoar.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2qbgkjinv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxyusk.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2znutlhyq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2ouxyrqzb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2zvnggimm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ihevrhcj.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2lgbtdlim.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2thzolsmk.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gt2fasckctp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2rjgsowhu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2itbvoeuf.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2bstctjne.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2govvgqex.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2ootdsied.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gt2covchsis.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wbjnqhwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gt2akfqkyqm.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2hndfucmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2oqtvykfr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2yqdqdagz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2mbgkucbp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2zwzjzpij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2fwpbamxm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2oxahzrvt.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2rpdocwnl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2jvbrzpsb.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2bzhpileb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2rjdoiiro.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2lvpijgaa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2wwanywxp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2waxqedcm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2ztnqjuon.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2mjwnqdsr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2wqulrqij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2xmbqplnj.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmehbts.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2qjcchcir.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbopoghx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enmwieoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2wsciucoq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2iknutamx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gt2itmhvpce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2uvfbefmh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2upeksxfx.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgbdfyiq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gt2gfmjcufe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ethrrdqf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2lirrcxid.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2kzpuwedj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkggbqar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ektijwrh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbmmxcbz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2fbojqzxw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2odjkkcwk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2mswlzyzc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plncxkhs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2gncchqfk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2trjnsanr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2kqakkivp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2phzxwmea.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2pfnvoqtt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2jibyhkjs.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gt2lujbslcm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2kwbhchha.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2gzmumeei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2efiwpbhi.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2btktvqat.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2tpbxhybv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gt2jvxnmxyn.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2arzbeurc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2wyvxvejx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iieeyunb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2zebndecr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2inirtnzl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2hjonqznj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2kdgsmzna.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2bdcnhicw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2ephafbbp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2hdrmghgf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2eyozdycj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbghcoco.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nijbgniu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fskiokzr.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkckptuv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjltyql.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2akzawsrg.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2xfezdyls.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2hfvjjisq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2roaalzwp.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gt2znnrftss.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gt2wbgjunsl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2kdbndrti.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzcifvtc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2rrrclrku.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2prgakkfk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2dkjyuvbn.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2hlnwhgri.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcppppkr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gt2voygftwe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2xwxnbbgn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2neyndyjg.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2ensvudzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2qysbisfz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2hefutlaq.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2fouekvwu.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iubyuvqo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2nbgrslfd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2fuxotcfr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2twkktepd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2bpjkmzhs.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gt2kzkkoxha.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2scvwtbea.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gt2tumvsdau.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2ydaeotsz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2avvelheg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gt2nutureed.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2gcrcbhrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zackioxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2lptinzkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muebyuvi.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvakblko.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gt2srzxptvh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2swffcjwu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2tmauhrat.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2ihfezumn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gt2srmuivsw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gt2hippimse.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2izlrezsv.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2pkefcdmq.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2cprqmzbv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2phfdhist.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2dpssyxxf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2txjezjcz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2upmmkfag.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2mzdcqspq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gt2gaonmizr.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2kkpdshzu.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gt2mlnrrbte.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kltzzlwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2dtacnnnq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2damsmdho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2abqfalsl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2wztnstyn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2ndilhoaz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2evdkmgua.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2wdoiflnb.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gt2cqsfxkek.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gt2kodwyjyp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2dczqfmur.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2pvkjkwdp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gt2zfclwfoi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2vkqgwkea.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2ulfiilnx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2znxqhino.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehtvroum.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2rmyrnaei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gt2ssbdtubz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gt2ialdsrxy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2dvzkcrsd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2gbdwfrqv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gt2xirrwnik.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2cjxmpdbk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pddwhcdv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2rkydznql.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2iglafxlz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2rypihcok.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gt2seznuprq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gt2ckcvbfpo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2yosbtwve.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gt2tuebgzlh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gt2nhiujonx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2bojmyifw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2hccrkrmy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ocjlijpm.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksqhglbd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hptnxapg.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2thajuycr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2xwohspqz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2jtlpksai.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ftpgvgcb.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zgjkndwp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2cttfpyga.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2dmnrggoz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2ftkhpzwf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2wfzeljns.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gt2osrzmiau.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2ttfnxdff.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfatwrgi.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2twzxpcqv.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2hmfiljge.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2pluzxaot.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2vzmzednk.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2iqguplhg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gt2jcekkpui.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2zypahftb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2lfpdbjrn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2comuzlnq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2virkhofs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2dfifnvpk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2piyconif.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gt2rvtpwgmy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2tcfwocfx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2ntackhab.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2wywpvqdo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2oczrrjyx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2xeeelfwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2wvctgzdo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2knclhfij.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvtirjdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2jyzwajxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2tgkaqeom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2vtmqrrkb.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gt2logmgwct.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2sesczbtv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2udktenhq.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2rxehdoun.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldlaznoj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2juqfuuoq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2rmlckifr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2qarumyed.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2vykbqzky.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2oexjktun.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2xpdhpbxa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2anyagqcr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2vmjnovak.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2rqopifnm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2yvdnzvbu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2tqmudfst.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2rlhmrlxr.html


<!-- 参考信息 -->