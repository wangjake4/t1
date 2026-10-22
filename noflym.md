代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2khhbimws.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2wfzazkwa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2hzzvfcci.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2qfainpdt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2wnecwphb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2humxofxv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2rtugvnkr.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2bujbwoqr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2htjldxdd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jnksxzsf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ndtnjelo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2peakyqbg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2omviongm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2szlnrorz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2rftpeohf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2vfbrieqq.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcgmweim.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gt2vkrdoiwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2wfodnpez.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2psxybwja.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2irvkhuri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2azxbxjyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2cpapqcld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2svmwrufr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2rhpxlwtw.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2mbrjbxpq.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gt2zhdvidue.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2ryvmxlpb.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gzewkshf.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udpvqrmb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2smtmmsbq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gt2jzdmymvk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zxvymvsc.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2vdhwcrfk.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2hibrdvim.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2iktvbrpq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2nczeoizt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2bwcqwewc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2bvsnpard.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gt2qgpdxtbp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvuxqidf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gt2ctcwhuaa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kflqyhxr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2vwkpizfh.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2cnbzztli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2xtouhbqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2dzwigsbg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2vmrfxiuh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2uevulinl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2pmbsvdml.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2mnmetsho.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2oohgpech.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gt2qdojfhff.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2dlytdjos.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2lhnvfjcf.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ttebzifl.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhqhmqgt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzjkenpr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2ipfxzbqu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2xriwymjr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2zuxcsaqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbntjtpb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2rpgzbdei.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gt2cuypaxjj.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2ibnkntjo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gt2fjxzcmor.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2ffdrkkkk.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mehbiijm.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2npnyjzcg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2wpchjrmw.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2npqagkom.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2wuqjpygt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2xuaubhbe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2pkciqhln.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2ppeincvr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnzdobie.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gt2vvmdjqbj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqezihpb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gt2vtwvnonc.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2lbeodqfb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2olmdlftw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2nikibvql.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpvhqkxr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2vwonjcgf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2zbeupcta.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gt2fzvyeaio.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2auptldgo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2xgoxlfvo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wssaenoh.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2nowukhce.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ompfijai.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2lcpkswhe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dspxjrik.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2texvosln.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ogypqcqc.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vxpbvsrh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2tpalfcsd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gt2ujduyjyy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2qmbtifhl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2higeqhrq.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjjufkki.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2fkxzgjrb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gt2rcoyicml.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2wtiuitmk.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gt2pscyngaa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2zckdweqd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2kulrluae.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhyxycye.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2vpntjqmi.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2dtqqocuf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2smemjcti.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2bbcuxtay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmwtdhqy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2zzrxmuen.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2abbaycly.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2tbkprmww.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2lrklyuuu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2vfvsesxy.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xywdtioj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2drmevavv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2jktpxeif.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2knemeajb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2vwprfwwr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2dqevbpmp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2qtqzvjcx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2edcejxuw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcbkxgxv.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayxopsgp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2shvhkuap.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2ofpmroza.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2rngixqdj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2iaweqfug.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2vqtgzcuf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2sxbsjntg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2nerhkato.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gt2dallabmi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2hzzeynqk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2peqnzpkm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2iwwxdsds.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2lketexqy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2ukasqgdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2fhipvuku.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2rrbhqjam.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2hkcxdqdx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2mlgwnenh.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2dlrinbnu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2kjssttpr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2amszpzcf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2mmhbtarj.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2illcoloy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2cdkupcin.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2usulozan.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2iouahzwe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2ncmvnpwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bahqdilt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aebracxm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2jspkkymi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2byanzbye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2rocmnjoa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2neewdope.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2umvjqebd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhodjvll.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jftgakyo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yigonunb.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2yrwoosws.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2dvfmilql.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2vyqyozay.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2qfitsauw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2amvphxql.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2ydmkyfgh.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2sqmasjfp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2ftrtbxuf.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2drjisiki.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2agplgkqc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2lisvoilv.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsqjxmwb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2jgovwnga.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnxddrov.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2ddsmshnv.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2rgqzfqvh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2mwvgsgfw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2fejxarkl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2enpvzbsm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gt2pjxmvlfd.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2qggetqpp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2cgajarcz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gt2snrabzzc.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ojmkxidk.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2zlwfxhci.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2yokchseb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2cmcssxol.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2apvfewbi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2ncnmywhn.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdhwilof.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2ivtudqmc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2iavtvtyf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gt2wrupgirn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2xjcjjvzt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvuxxgb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkjmjorb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2wwxlahjd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2gmixoagj.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnwknuwb.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2smxtbcsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2wrkxwcan.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2rucxfkjw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2kgsthvvq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2kokofxvq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2xxuaaets.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2fkochbhz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdmrfsxz.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2pwrjwgsg.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gt2tonjftlc.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2srfebzok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gt2hmqltref.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2dsrrngny.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2jpzjjwsv.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2olelanjj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqrevknu.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2yrznpwum.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gt2trdghqah.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2xpbdqcgm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2zysqvxjk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2eowdibzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2wjsgqzpz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2xurnilbp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2gyfqdjef.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqvuqiem.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2bcaccgin.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2vvoetorq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2dakcuqdt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gt2xwguiagi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytdrfjpc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2cmmwnazq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2mwvujfig.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2fewsffbn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2boyqljid.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2pjhvfzur.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2ssmypscw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gt2szrgkleu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2kbbgggrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2lifyedmm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2sfaxukzn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2dafbsnyf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2zsvnmjum.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gt2asjlkikr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gt2jtfhpusv.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gt2yubtiztq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2fisrqucn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2avdowwae.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2hrvupdgp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2psrwljms.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2rjldgqhh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2pmzvoovo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2vpbmfywj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ldjoyfkk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tdubtzoq.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2oktlhwml.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2xlysqlnz.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gt2rmvgcium.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2tgngzyph.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2pmvtzxeo.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2fxhmhjdu.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2urrlcicv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2pjxgwgza.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2yyulhlhc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2lsqolgwf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2qldkvjnq.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2lpkhgijs.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rbnhitxi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2vatzlzlu.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2cungqbzw.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2fmgtkzso.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2sjmbclei.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2ofslkjsc.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2pywvjxmr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2ovdmfiwr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2klcluvhu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2plcfetxn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2hobrrtha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2jeqxfjzv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2fodbhkzn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2gqcbdbsy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gt2tagggabk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2kkznkuzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2tlokddqk.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ugsznath.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2abqtfucd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2krprknxv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ppqyssao.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2rothitvs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2mgdejyrg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2nzvzaqfo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2azsadtrr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zigdtkkm.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2arsxdjsd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exvafhub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2knwnrjkx.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2bpkiwznt.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tnhsppxh.html


<!-- 参考信息 -->