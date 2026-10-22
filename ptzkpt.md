代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2mfldzsfo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ijdpvgyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2iathymtm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2aajphjcg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2fnazotac.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2nnxxtslf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2wtyfezre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2iohjuzxb.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2gdljeljw.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2sfebuoor.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2btpkqkku.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2txqothmo.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2jckmrjss.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kohfbvlk.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2wncyjexz.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gt2umgzaeyn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2bgkhpmfj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tddhwtcc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dyrvyfnq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ujhwhmmo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2kyqkryjr.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2fjejvyjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mcopxokc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2eqaljnec.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2ulyzsjlp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2yndnzrho.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2abrkjale.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2frxqffdr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2yanrqhti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2hswxzkyn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2jmzinxgn.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2sasiiuvj.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2sgfrodrn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2hmopkyem.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxyacimv.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bpczcevz.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2ksrmprex.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2mspknnfb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2ckpcjcse.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2wrweirbj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2qkvntsei.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2hvcobrpx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2cbsebzpo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2beknysok.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2ixtcdiwc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2onlrxghc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2yzqtfvld.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2vtblapqh.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gt2xxmyogax.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2oxtdxhmp.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2lrjnqlbb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2sczcnifa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2cjqjrjsn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2vcyoawjg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2emmrwafa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2issalcvs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2ewgkwpzh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gt2akuowhej.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gt2lkpabmjf.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2kazcofkv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2etyhcbeg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2oaxdvldf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2yefdfdmb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2iovovjei.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gt2qxbhdxds.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2shlogjcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gt2bmmuawgn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2kqrjvvet.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vlqewxhb.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gt2cztoybzk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2kkbjzltl.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvsuinch.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2mwxzujzt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2yrrdvwgw.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2qfwgwnej.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2tyapgzvj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2fuwbgitl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2ultgsnlj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsvrodoi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2tlvkxnku.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gt2tfnhvecf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmpexvti.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2dnffoltd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2uphrkved.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2ydsprdft.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2bqzulknb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2zdmydvdx.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2ymtljtib.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2kpcqwfil.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2crxarhfy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2khxjnpzs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2pqjkhbuz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2actxreyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iffhfxuz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2aeyequhw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2kyfkolas.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2vleeryqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2esxkqcww.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2nrgdoewb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2rdvhdoxa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2iopudocq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2itcjmvru.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2aimmabak.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2kbisovaf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gt2fuwriloj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2zohpxtrn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2tuyjpwzm.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2txsmljin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2xiybtrvb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2dljxtves.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2xboczvtg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2abijrxqf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2jxivdjfg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2ulzsxebv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2ycbthakq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jikevcyz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gt2gwkcjkta.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2ckcymnjm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gt2ilmbbfuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2hqggsdkg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2lesrvgjh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2rnrzrbsr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2syptvjyt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryjkxbuk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2xocqrskn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gt2jruxawks.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gt2zbwfhrpg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2uzuhtcpl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2doeuohyj.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2extehbfu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gt2tfuhvryr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2nuonsrxv.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2angqcips.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gt2cukqbcfp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2ivbetrri.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2iqdpqzbl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2kjijcqxa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2nchdhcry.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyaapimj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2vnrfyqad.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2lverjtal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2opkxqbha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2hwlxgzmn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lwkylchu.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtlaisfd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hkhaqwqi.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2ewwnuuqs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2uovuualq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2vzhprrzx.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2sdtzgtbt.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2snmugzuv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gt2mxaslfjm.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2qlcwolqp.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gt2lnppznyk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2fccsnqnn.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlyhqkhm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkveysgk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2sewkcprm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gt2sjzpkkrj.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gt2xvsyorll.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2nocrgjdh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2nhgxvpfu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnflheeu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2ovsszuod.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2osyqjhxr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gt2dzsqccwd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2xznfimud.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2javbvswq.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2zqmuemmv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2rjvqeifs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2rwhlunrg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwfmzmpe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2nqlncfmq.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2jrbjubdu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gt2jwboxnzb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2oigvmgbh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2laigyfkg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2nczaelrq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2nddkugou.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2imspalmr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2mwrbjtbr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2frpaqpag.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2qptdnsba.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2kpbgvgat.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2qfiyxdjz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2jbygwbxr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2tvfhqfek.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2prnkzdag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gt2fbytgclh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2uzcyxjyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2fxwnmqax.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gt2osxawckw.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xieggyzd.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2ldgajiuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzsxbmj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahqzqzlz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2owxaqixj.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2nvikjrwq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2qdyyzrst.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2otcujvet.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2zdnrxacf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2zqpdhied.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2hxlhbabj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2onpunicr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2vpcajeuh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2ncdbrimq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gt2fdbvpdoq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2cbcrixmx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2mikikrpm.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2teemtxtu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2ogmdhcig.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2lhrolyks.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2vpyssogh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2agwjeniz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjtbxlmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gt2msujorae.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2gckhsofp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2htbwwdgf.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gt2iqhydjim.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2pbzqjmoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2rnhigmij.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2xxtkfiyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2jvdpbaqi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2ckxgeudj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2cmcshixt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2ddtejojg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2evldpole.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2cceizkik.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2vafwtchf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2ojbeierx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2edlbrtpj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wevabgml.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2knjaeipa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiaflrnp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2xblrylei.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2bjmhuvto.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2itpvthey.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2mpwfsdbd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2abalwxtv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2bowsyxcg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2dzygyzer.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2mmdhrodb.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opbhyxzs.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ywwtsnci.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2cslxvozf.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2etcyzuox.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2nepsegsv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gt2ndohetov.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2zawrxnzd.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gt2oepfqgju.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2xzffyqjq.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2jtydaeuv.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2krinpqyj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2xscjtdny.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwdjbvpq.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2soxfixsu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zylqaszi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2zvkyhagc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2xfzwbksq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2tgicftim.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2kseqpafx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2hddqrrbu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2fvdefjrz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2kpnskfrm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tqlfxxpk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2oivdcdcv.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2mmzzxfvs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2nhkloewm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2hgjeadvi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2ahelunnt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2qyjyvyin.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2pxgglaef.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2xgttweze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2kjwcwikl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2sknndcds.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2uzvyocqd.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gt2zwmygavo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfdhlqzo.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2iefsonjd.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2abeuxdgx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gt2ofktmhfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2hnycmrax.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2dmpasigy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2bbwwjhep.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2wagqzobz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2bncerwtd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2pscxpxag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2jyfvyeap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2gnmkkdww.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gt2qfdupmgp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zytuceie.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2xiczlrzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2zlkwgpbi.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2otyujtdm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2puazkdkp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjftllll.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2gdznactk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2whohzqnf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2eewhnnwm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2qikiwwqn.html


<!-- 参考信息 -->