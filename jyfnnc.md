代发 wailian999

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2ukckbvtv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxpbbmpj.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2ltsluzaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gt2cptpizzc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ecgrucby.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2nophghqs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2fubtwntv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgvkhuxp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guacnxuj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plogajsf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gt2levvykma.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gt2bkooxlxq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2dnalmcqk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2xpjbktxb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nuepzjef.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2lsedeytp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2yhdymhfz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2ltqyvfll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2fybgzyry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2dnlquhjr.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2tjondvfb.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2gnkiflaw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2fqqgemng.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2qmysyzbu.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2mkpclsyi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2nlcelbsn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2qtujgwln.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gt2fnvfubea.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2dboziygu.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2avdixgmg.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2dbhhtbwy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2tfxjodre.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2uakdkfru.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2bqyuyirh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2bsdekinv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2vjiescup.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2gutkhnjl.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2nsmgshjr.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2duzawihh.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gt2tvnphgiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gt2ifqwxxtx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2jfvssndz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdhdvekw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gilpjjaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2yrssehoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2ahdynpwc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hlxsekjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2ulgvkxkd.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihhnnulk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2auqbvbnr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2fasmxsju.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2rfuiqctw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2iubiohmv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gt2etzopjnb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2ymzsfbtl.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gt2wmqrayke.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2cndntlaw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2azsvkifs.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2gcqnmcqf.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2hjvlczkn.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2awcmmhxv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2vsqmzxkm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2cqwbgips.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gt2qcjqmvtv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2pvkuebbe.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2xekiftgo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2ffdshkgj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2jcgtfkth.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2kkqivvwk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2vtotjwpn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2napbxrnu.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpjaizpc.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koysbplv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2obrdsgwa.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2qzuzcpvm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gt2pdnmagoh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2fcelftgo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2diyhxczo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2pxylhzpf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2gzvcexma.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2dyjffjhh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2owmigixy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2pcdtyftu.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2ndlvoqla.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2rstugxsv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2rcvmzyyp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zudivggh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnolunyf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2cdifwwlf.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2ohurgcak.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2qqmdawbn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2utfaxbet.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nyurrsxn.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2uyhcpcaw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2iducjguh.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2lntevwll.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2wiywlzou.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2kqczogex.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2wfjoylhe.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2mpjugsji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2hhxuomai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gt2avwojlbu.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2mdgqblzx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2hgkswxbk.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esleasgs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2rdkvsfkk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2hnhfxhyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2bleqbyaw.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2eoyxpbva.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2nrmnentr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2psqjaktv.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2ilwmfdnk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2oanepyfp.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gt2syjotxjp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2efbiiogy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2gowphpmf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2xecpkcoj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2wsobwrrl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2rqgkvfdl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2bjlospos.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gt2nqbryeyy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gt2uuynxgpm.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2scinqccc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2qgakvjpi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ddbgdsmc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2pphufuat.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2ihihflly.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2fnhwycls.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2ndgxbhzl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2pclgylts.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2hrvnqklm.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2flemozdb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gt2kvfblsor.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2vwppxfmt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2ukwlacqv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2kogsmpar.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxhbhboo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2cycctust.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2lmbngifa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2wpewdfqg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2fsnolasy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2lrtknjgt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2auvutvwo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2lmtuvaoy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2mpaloopl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2yenrtdba.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2pxiunugn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2ajwhihee.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2wqziauda.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gt2hqxbrsuz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2necmwjkx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdxsssbl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2lsndiizx.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gt2rdithiye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2ljmnaoco.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2ntlorjnm.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2lejafkva.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gt2plvohdbc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2cimctkjm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2ighhcfvv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyoaokim.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2pvrbgqvw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxotqsgr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2svjeimwq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2ddovjxor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2abviovyt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoxrswkn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mxqkarhs.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doeiauub.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2iqhjvawu.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2twcjvxrh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2getrvzzh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2hawrptyh.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2chhhmpql.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2ufigpdng.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2aftqjjfx.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gt2lsinluew.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2feqftaiw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gt2zdtvoybp.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2cjpnaryu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2eabpikpy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2hiistzqd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2wklyhfkn.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2ovkdipsi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2lsdlgttb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2ltocdens.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2bxvimoyk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gt2odljobgn.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2fdklfwpc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2ygabawjr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2htscqqcj.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2oxgrxlmj.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2axarmuxa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2rmwjgwwr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2ovgtmuzk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2vjtbqhsj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2rkgrcmav.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gt2dycmtgbo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2clpfsmmc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2ogbogjko.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gt2onsmwueu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ejrkbdye.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2jzekoxbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ohkyeszt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2tpuxnziq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2ncnmncsr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2isozpkfe.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmgwymrw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2dgboygvd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2bpforcvo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2lxewibzz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2xemuwdmb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gt2wdzyimfr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msikeqwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2diylzarp.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gt2idydfvce.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2rjmuutsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gt2ipbscvqq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gt2enbhkckt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2clubrbef.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2pspshswt.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2ywvepqgr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gt2uvkmbtyq.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2iiyvgzvs.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2nuqboeqj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2ijunknbu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2nuqmfpeu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2fhqmsqco.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2efcdrowz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2ppfwemtf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gt2riyqfuin.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2ubfyakdb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2zkyqompg.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2rqghzqsg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2leiddcjk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2ddshvqui.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gt2hoifmugl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2tjficheh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2aygaucmh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2pbgnlpux.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgtbliop.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2wkxumsfr.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkewtid.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2ezojsnqh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gt2nyuerjfv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwecmign.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2efjecnop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gt2qfiqjzwa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2dlklzqko.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2ulihuvqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2yahznhvt.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2toofzjfs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2eusexphs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2iugbhctc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2xyfqvdca.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2bvygrkvx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2vbfufovv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gt2ebkeddfi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2pvrosspx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gt2gowdkfuv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dakamoug.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2dblnuzuw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wmdoczaf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2gdkeerrt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2hgxipkzw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfdheqsb.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftuvnbyc.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2jlqbaman.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gt2ucmtiikt.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ptygfede.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2akdzsehg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2dkcmqytt.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2oqfkrwvh.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gt2uthdlmsk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2rcbvblkh.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2cndgokez.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2kvlmklpm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gt2qlfuucal.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwosssqc.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2yrsqfsmn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2snnznenk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2hsuhlvms.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbjmjbmn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2vwiekdzy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2jrwdgvnm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tszriuai.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2uzenarsc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2unslvmue.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2fadbbbmc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2mgllqxfp.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2qlnvudss.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2simwhucb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gt2vqmxawzc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2pemrtwbz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwnjtibk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2itsyntur.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2neiddsiv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2comgqomm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2pxdrdrih.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gt2jfplfvoy.html


<!-- 参考信息 -->