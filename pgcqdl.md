代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2zrodqqht.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2lewsclrw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2fctaysuz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jpkpoxow.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2kmxgaras.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2raojghmg.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2wzyytgpm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmtonyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyirqewf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2vamqlqid.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2candsgvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gt2tsqexkbz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2jzfpjyjh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2wewolaxi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2shsvbqir.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2pzhkuymf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2ojtbxbom.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2wunmceuh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2pamtwqtj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ugcddica.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2wrvjbrzv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2qszlalwu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2yblpikvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2snbmxogw.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2xthpzmmp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2xzutwfvv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2kmooxgdw.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrhnbvwz.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2omwfaept.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2rempgzlw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2azydfhxe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2aummkxww.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2anfbvcxq.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gt2xbkciltb.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2sbfehlnk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2drmightb.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gt2dsmpfwrt.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2agotfroh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhgtavin.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2kdjmwanp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gt2gekttnyn.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbmyekac.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2dqdfygst.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gt2inrdgdyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2yqziydjz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2slsfqgjg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyfadvlo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2caaiybzt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2pcgktyls.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2laaojlqd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2vpqrzoyy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gt2eqcqqlji.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2kixecfmx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2diqeluib.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2eauljqnj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2fflothpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2smrottyl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2akicphut.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2kojoqoff.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2ohejrzlp.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2srepcdda.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2pvwlkkuo.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2twgxbsgw.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2qoyrguqv.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2zmbiijtg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gt2ihvcirav.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzhjljab.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gt2ccprrxzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2cetzjltz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2qexdxipm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqpxpsaz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2yyuxssko.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2mldxdfyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2imcuohwa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2tddsxxry.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2axtqdamc.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2ldvrlchv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2dqdfqdgz.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gt2hibrxfav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsheqerk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gt2mondvkjf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2ktpkewhg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2fhmfyubp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2ajykghhv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gt2agekakvh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2twrnelou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2rseretlm.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2xrvwklwj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2syydbtch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfqbwetu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2zrljvuqp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2cuadruua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2zpyojbku.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2amhqmkev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2zxzjqtdz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2wdtnnwto.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wgtjkwkt.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gt2kjnvvzoq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pqkdnjud.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2oriurweo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2wmjvpckp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2iwjytzwr.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2shzcaahn.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2wfmvvgii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2mrvcsgur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2bgzihnok.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2plcemrkd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2eqgoxbyt.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ekasoivq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2hikgdgye.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2vworloix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2kjflruoo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2viuiioul.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ccgrlnof.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2rydzdorw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2tqbblwpt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gt2snzgfola.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhiewly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2sattucjc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2nvkmykpx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2kkwchyvg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2bywjuipv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gt2jfwbmpib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gt2cyciikzt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2mrjzqvmd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gt2idjapsnb.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2ndyborok.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2dofieoqh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2hgcgdxjf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2bknuhtcb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2vkvlglmp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2mvfmxpbb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2vlahjpog.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2aopgucnp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agtgqvwb.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gt2fvxdgcdr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2paapqbbc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsawfzeu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2raozgqgx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2unvnmdpd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2xndaajzx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkfxkeju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2uqruajli.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uonklsvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2ffrcuurt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2lqqfbfrd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxfnucnz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2mbbvywtk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2wieyxoxa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2pnegldgp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gt2eyzeygpm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2bishgqyk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2mfqzzdtq.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwlwglku.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2qlsrxmbq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2ehdfnsnv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2elmtkatg.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2qjvhrosa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2qvqjfyyx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2kzzvsmrz.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2kytzjrlu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2kxwvspfx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2rxmycldd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2zldjukry.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2iudzeuvz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2nsmhfzou.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2sgvbefmh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2xykcwwha.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2sybffift.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2vnzdctgo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2bozurwrc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lqkxeabt.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2ozkdeomy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2csjpgtor.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2hemxjafw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2gzjrhyxs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2tlmwawbw.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2oselbzqj.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2vzjcifvo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufzbloyn.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2rarggjpr.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gt2ztfvihid.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gt2fiqilitv.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tllaxhlp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2tycupozf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2evwokbvh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gt2oezzyyfj.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2giwlbrmu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2clggldqy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zikcggyn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2kdkiolzz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwqrmdvd.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gt2tegechoy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gt2ikzcqbua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpaceaow.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2kmojwily.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2yekuudrd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2ubklcczc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2mqcpgiaj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2opezihse.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2focrdcfr.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gt2zaqcgnzd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2qvlqjail.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2wxppbecz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2hseysnfh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2kkeuevbg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2cctsonke.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2dncbuvca.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2cahudtag.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2gswcirmd.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2gkevoykd.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2wjlifnmp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2ywakmmsb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2gchakzht.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2wyvpcuhx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2luyoazup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2rgtyejrf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2clvchvvz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2jatueira.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gt2blnhsjbt.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gt2tvmrbitu.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2aqntqbsi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2izjswmii.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2xlawjpuw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2uywosgmt.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpqygjsx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gt2droqnhlj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2qtfsszsz.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdvqnqtn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2pjotsnvv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2uwhgypry.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2nugtonlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2rjrnwgln.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2yuecilfd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2jfjmjwku.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2spxudwac.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2inalfkst.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2lqvjbbmn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2psihmgoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2idkthcjg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2xwivtsxv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2qedlcxts.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gt2dapweiaz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2ysrtiyxv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2fmocxshl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbtpplnm.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2gadnupoi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2hfoslmmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwfpnply.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2aczysoxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2ahvmtejw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2pfzeszgg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2dwmlofon.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gt2poxwatcx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2dxdjgqcd.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2pabxcnwq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcdstskh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2ynryvpgu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2etiyklxr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2gggidcsi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gt2oduhjpft.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2purjlwcx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2fghwolmy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2wdtdsven.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dhmbovza.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2azeftgmj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dezbvdzx.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gt2oekouesy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2pegmseft.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2nibfrola.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2jhtcskmm.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2dfvxeuwe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gt2bucuyssp.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gt2nzwhesuq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2polqvftv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2htdzephy.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gt2wcrzehgz.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxfshfpa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gt2oynwwjzl.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xqruvsum.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2fubcriiu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2bfsrdhmh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2clyolqal.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2vytipzbv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2lzilgdrc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gt2lwpzukcf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2arfdptsz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2bctjutvg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2jdlgcapt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2wmgveqih.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2waxdkqmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2qxctrybu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2bxezquwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gt2kksvmaie.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2yimpgtwq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2ewgfwysb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2qmogpdvx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2ymqguwps.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2mbdrsdhv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2djgnqdtt.html


<!-- 参考信息 -->