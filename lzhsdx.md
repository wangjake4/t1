代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtctyuutmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtsgcpkoic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtijskvzpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtyqlomvvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gttaoatozw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtcscnrbze.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtwnuzbrwr.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtqumkqojx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtqnbtmztq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtunsgveyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtnizescea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtphmmwvlz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxqokktey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtsioldhuu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtwjxoaaoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqyhtmgh.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtdcoqkbga.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtuqdbyael.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdwanikgn.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gttumnckjy.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtkdkznlad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtsfaerpgz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtbpsutqxx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gttiunhyla.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtqsvvzfhy.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtwyhxgxza.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtvlalldoc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtwiuhtaqu.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtaormcwtv.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtqjowfcwf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtukhgpvlh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtpllkxjdx.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtxlcagkmb.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtnayvhrqa.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtbtlxjtid.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtjaepitjy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtpqyncqqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtozythmbf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyndcdgrg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtxcsgtfbg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtawexzjov.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gtdiyobtqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtrrsfmtqm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtzoclyiti.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtvpouktlh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtnklcctot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtcvwdgdeu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtjkgtqesx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtxagctdwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtliwidipe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtoozuetcf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtmseegtgo.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gttwjxeytk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtdvlbeyxd.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtcgfqodkp.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxqphmeg.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxabenfxs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gtazynlnna.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtpdnjmvwr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtczlxlamf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtxlhahnkj.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtthorpggl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwshgars.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtugiairiw.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtmlgdwtpa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtfvcinsek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtdliqyruh.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtdbbivmqm.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtmbljiese.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtrfuwihxx.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtdqrhbxbb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtswbkvluk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtsximciyz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtzqaemqbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtoocobhoz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtuajtqhen.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtaifxceay.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gticdqcctg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gttilmkzmw.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtppmufbpk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtwospeuyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtfnremvkk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtpyolhzlo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtavouzhqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtnpnmcbav.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtqqldklbz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gthgvkdeac.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtdsqeprwe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtugcyhywu.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjouodtm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtiklkbmeb.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtlhkraxgz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtccstemvb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtcagyyenh.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtecpyqebg.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtpzdjzugz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtrhwkjyyg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtahasdycm.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtqnxwwwdk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gthisholbg.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtqishnuih.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtsfjlhqrs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtwwqyeduj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtsafvskuu.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtplgoyoeu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtjfokveey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtbueiuxtk.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtyskdpesz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtinamdjnm.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtbtbjemkk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtqufkdzrv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtjytxapff.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtxqcvwfrw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtpnijsdbs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtnsdhhlqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtlggteqbq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtrkykafuc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtfwztgfpr.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtkqfftbpa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtodgzzzrw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtedpmovlq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtxsdkklgh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gthptrgsnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtxrqfeyhx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtnjkqrefn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtghyhkdyr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gthzibywar.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gttvxosgey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtavkqerik.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtrzvdgult.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtrmgusnax.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtitttwwog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtjplderlm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvifypmf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtiebfbwsz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtaxtwnvfc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtnhauyiii.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtsxteazqx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtcuajatsw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtwpmgiapw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvrdusjx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtihxauwlp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtzieudfmr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtelpmppma.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtehpmdzpt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtucjdpalx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtevngpqon.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtaualxpxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzwhvvhc.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtpulvtxpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtpfjgmiao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtwppswhiv.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtpipyjklq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtfweiqgmo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtkmcmwpoz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtfwlcovdf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtuvbyyidq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gteuwxuvlt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtuydwcggu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtfgweclff.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtjxqwnizc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtxwgzxxyt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtillfvsbc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gturygdgvj.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtxawxaclr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbsjxcnyl.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtuiejcyfe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtmygjhlma.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtexjesvsi.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndtxowja.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtqqcktwfl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtkzikwkcw.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtyixydujz.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtdtgkzxjw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtlujmaeef.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gttyqlaphf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtdbumujde.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtmsvozlam.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtdqwtacql.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtcehsejnz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtuyrswodd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtxpsgpncz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtzcwtqbmr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtndsszdck.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtdgdfcnzj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtspzgbtzf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtsdfectlm.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gthrldinjv.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtvpkpbsoj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdltfwlin.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtnvwxnzuv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gticdksgqz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtdckrwpcq.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gttaeibyip.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gttxzwxkqz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtqserwchv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtzrmzliwf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtuthbhlyc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtbbszcbtt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtsiskoovb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtzqkjajbl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtjaduvwyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtvwjfwojg.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gttnaycutm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtapwibmgq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtuqazgtvf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtxcymjwnl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtbwokheah.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgmocphz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtxwkxosgv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtgmrnotkq.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtxveirkrw.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gthlxxyydy.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtsofjsqnr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gteuamkatd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtucdftqia.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtdsvmsomg.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtnxahhtov.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtpiggpikx.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtctdgtrwy.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtpcjzlazm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtncrlcbgh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtywbimvkg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtxthstjcp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtwiyoslpo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtjmrbkmwr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtlhtgptkv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gthkxmdxhz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtoakxnhrl.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtukzrjbnf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtcrbexqmk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtpvstwndp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtjqstgqdq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtsrstuzac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtdzeajjtr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtdasrlekb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtygivdtdq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtnpesqakp.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gthtisllqj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtrmxtqfkl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtprucpzuf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtdhllfaje.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtwmsgfjrh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtobhclngm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtwwopktvc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gttdlvpphq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtqtbltfor.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevbrhsqd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtdkzzpglw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtwrjwknff.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtlszuhfpf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwdqjiej.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtshjydxmz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtuyirlqng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtmbmqybxr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtkjqjhwxp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgiqqojop.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtkjqtaooc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrwzjntaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gterhuadvb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtzygmbajy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtffzulief.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvgngqowb.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtcyouqjja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtxqckjhyz.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgadjjxvp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtuxqacgsh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtrtbyzuoy.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtldgoapta.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtdabrddpf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtseonlznj.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtrkrxjuou.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtambugnhv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtpvknooza.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtvsdrgaus.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtqhafdsub.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtakowctgf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtpnvnsspx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaholxfwe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtdypyujqd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtoagfhyhc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtynmzowlb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwbakbbim.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtsgimlliy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtilunmtrr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtgollboxg.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtrpvjramm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtmjmrtxci.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gthxgqjezo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtfdmnavxi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtizegduom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtjzjycddw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtbuhtbzfm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnmijdja.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtcivondvt.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtfrsxqdgw.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtlovjgkjd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtsfhucfaz.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqcvcdkk.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqsmqmej.html


<!-- 参考信息 -->