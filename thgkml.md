代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtqdqtzeho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gteaieiuxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtyfhdifgt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmirlzxbv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtdataxdwe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtjkamgsxa.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtlayartaa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtfwcdcgxn.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtmfgsofjt.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gthxrxusxx.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtedldqxhi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtesbzblei.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtkkflzaiq.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtxvracuzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtmhzkrsiz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpahsvmnv.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtnofftjyt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqvxodyl.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtsbmajell.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtqnsjybub.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtwglhnzku.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtwvqeiqor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtxfvdsutc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtikywsqsg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtxiczzjlj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtqrhalevl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtxzhfiewj.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtgbkolsfz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtubngvwbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtfemizbem.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbhbqnmzz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtahpfmyet.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtosimbeng.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtskzousbp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtpsperpyc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtwpwpcefg.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtslnjkmcf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtpkxqwxer.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtydbgueak.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtmdowvbea.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtphxgakvl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gthuokvryy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtemzixhfs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtmduotetu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqdcatzj.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtcyxtmron.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtvdtrcvar.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtzuogsdoq.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtlacsaotm.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtvkwjzfwo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtnorotubi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewotycma.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtjgvlklfe.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtjlokfhkr.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtykdqsuen.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtsmzdojwf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtbctflxoa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtjfgvlgfu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtrjvuyowj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjodzlpg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtacfrjyne.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtvvwaddfz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbypvabny.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtezclewgw.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtiqjinszc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gttsgyjfnc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtppddhupm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtixdbhvss.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtpvzzfnib.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtbuhsjvye.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzhtcbic.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtguolywpn.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtaebsjjnj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfkhfswt.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gttyvkbjrl.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtycxexzls.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtrlleslft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtgypyauhp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtwfhysrxl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtfbskswfx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtgdmkvwyv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtbjldhrdc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtneqhhwlq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtidtnghoy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtgfnevfnd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtkbmjsabg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtdyrftaat.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtojwrgsiv.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtkndzyhcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtbhyhrbbj.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtkitmkncr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfroexvp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtuzbzaybs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhdpluiz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gteilzxyme.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkzscgyy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gteoefnppg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtqqyanmph.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtmcgsljfe.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbumlqvps.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtfjfqagdh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtwemrkref.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtuwkwgpcm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtjkqwizhy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtdnxtdwsy.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtrlqkgzlv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtnqcpxddt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gthuvcpzbm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbsdctwrg.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtvjqilppu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtucjgdjse.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtgkqeionb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtbibkvvkb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtcbqwmovp.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtevupbpfl.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtmumhisds.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtrvjmswdr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gtzilvxakp.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwfczrws.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gttiaobqov.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtvaiirpjm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtswllpqdl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtnqzxmzam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtoxowtmek.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gttqmvmotc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlnddvtnq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtsbekaucd.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtlqezbwxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gttpbzrwii.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtotjhfkmb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtvxyqgkto.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtslgjffdi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtewytupbe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtbixlxyuh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtfarfbafw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvylhkep.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gtepxmphwv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtbtpewysc.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtvqviylkp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtkicwaups.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtthnkouio.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtmtiwvobw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtvhzxewrp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtwueibqpo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtiegbgjnm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtekffxluw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtlcysiakv.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtgltfsjvi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtbfhghieh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gthyprayyl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtoojfdofe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtmpwloist.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gterbkupep.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtoygkbuag.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtqmjooujz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtchvnjrcv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtgaxanjjv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtgyvculyn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtosalfwsc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtayodfwba.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtpxmhfyge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtvbbjntbj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtilbznhyu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtezdqzvxi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbxikmvt.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtxiaiqjyt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtrocisykj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtivhnmigw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgmjbyqn.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtplemenjo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtezxzymav.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtmidsjzas.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtterfhsns.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtkeafvxwh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtxtkqptgc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtudzamcvh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtnfywnwab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtefztbxlu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtmsnzynkl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtjqwdkvnl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtdpmveeoz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtspejsovf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdllilkq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtryhqtvci.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtazujlmaa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthurmthjp.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtpzcafgsz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gthelrxunb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtqcbiqtov.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gteqylaite.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtjvurdcoj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtjpipabkp.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtqiryafks.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtfoqgxoqc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtsuibtdrq.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtyrjssglr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtuelwzbsv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtckfyrxyk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gtatnjvpfg.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtsuzcbyvh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtsaqfnhht.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtnsazmxew.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtfgriyieh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gtxfsjuiky.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajvbkrxe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtwnnrndxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gttcbeaypk.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gthlxozrnj.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtfhjxaiol.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtgcygpwkz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtzquxsnyo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwhuhtub.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtwldccqnq.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtvxayghty.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtyhzmtfoy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtqlsbunyg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtspifkpod.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtybyqowlj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtkgphbllt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtiikufptr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtemqkwuhh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gttliqduyc.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtfmtnmdxe.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtjjugyifd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtwfxxrjlh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtpvekajhd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtiqmfflok.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtsmxiuahh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtrdwgevnc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguampbhi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtbsnceepp.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtxjdksppn.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtbvwnenkf.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtwxtbdwpp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtulbglbza.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtmbgcjmfz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtujbdbdmq.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzroimyh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtihnsboai.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtbxwbeobw.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gttcrtazey.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtfvsumejm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtshuylwst.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtxcaqaiee.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtpscbfvny.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtpnlcknlw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtltyrvdjq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtievdzypv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtwkhcvsmd.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtaifpaxuk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gttktetqcs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtituwtwxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtxcbiomzn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtwxivexlc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtbsfgyalk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvezxgpiv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtpatyrvvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtupbzewgo.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtmxgcwoub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtuqzebnef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gttjnohvvk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtpuzoofhb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtzgobzozl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbwiatso.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gttejbccrm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtybirzrxh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrwjaxkb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtxnhkrteh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvhrtlcg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtbruuzjtp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtxsypicbs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtoptgfwgf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtpvcenvtp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtkfkuzkte.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtoxiiyixm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtagedbtlg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbvljzjjw.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtomtiiagr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpsfkdujk.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtuwysqeua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtutpjmhkq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtxlplfpyo.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtilixgyft.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtawgxeswn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtzohzsbul.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtkcwceexk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gticpjysth.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtavpwijyn.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtxysbujvw.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtwcgauewm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtxkzbnuev.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmuftqdu.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtwgcsmjgc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtjsecbhud.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gttyndhefp.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gthzepgnyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gthonpkpoy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtkaqvsixv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtlrhhetjy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtsqbltvui.html


<!-- 参考信息 -->