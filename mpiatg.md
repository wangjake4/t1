代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aydscmqg.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2lcyjnjga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gt2qlkxkyuo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2tskgevku.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2opvylytj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2gklybuke.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2hnwnayho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2zykwacsk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2xsaxdxjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2amgctfwj.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2jceudylc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2eyyxcnwq.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gt2caxuctox.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nrrnzpbw.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laqycsba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncgktsvu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2kuxhosba.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2yjccbzak.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2brkyfnoz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2pawxamnl.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuhkhers.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2njkgrxdj.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2nucisfag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2udondmvd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2kvoobfqk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2hdcssbas.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2xijuzupm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gt2aztyqhfj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkuwecnj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2ixstiywi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kelhjdlj.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2ywtngfil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2hgyjtldc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2xduxlptq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2objzidul.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlolxdnq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2znwywktj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2vujcsmvq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jcrrthgk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2izyipymq.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gt2ehxjpcre.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2meqjwxyu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2hixljnem.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebzixpcs.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2ldylkrkf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2zdeaaakz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2bdtokisl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2zmqexnep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2tpvrmboc.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2gwgqkkao.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2xiighgsn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qdlmewfe.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2yzdxcztb.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2opvzopey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2pkictyzf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2vhrgzllb.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2cwhdptns.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2lufwinrh.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2yfiuntgk.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2pobrzmng.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2osoavxvl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2hdxlecxu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zuteigct.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2uiwyvduu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2mbhmykxg.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2sntnzogr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2hegbmysg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2fxnhkamg.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmykdaey.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2rvxzerty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2wwrlpahi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeqypbby.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gt2azzsrogr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gt2abiqtszy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfczwyma.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gt2wfcwzmgn.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gt2aahdthph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2oclfholm.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gt2lxzatroj.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2bkfkfyds.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2lqmwyseq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2gllvipie.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2pnouszwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gt2pdxidgup.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2ctfxrfjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2qvkseutm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2nsvpiwtt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2pzpzhywb.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2zocxcnfq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oizzfaqx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2xakrgmwr.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2rfukfvaj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2jctiojwk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gt2vlkaddal.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2gyvvdrvg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gt2wrlsmsyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2spijngws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2mioziviu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2oytllhgz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnnuawpd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2ltshqoej.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2bccsmpgp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkmrscvv.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2uuedivii.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2gdzgffnu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2gwstvnpr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2riamxfre.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2aekpnmpo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2dlldwqvb.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2jjpxwsfb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2nlloowqv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2megsddgc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssxxjyaz.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2kjzjendo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2gfmezuqj.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2acdeatkl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2gzhqsfpy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2zfomdlmk.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2hgkbcrey.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2mevlpevs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2epnbczgh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2khznngsb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2nhhxfupf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2kwbfwtzf.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2ugnodlkq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2wcwkowih.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2nffssdbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapqeke.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwiytxsg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2jogojepp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2leohvoni.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2zqkahgto.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gt2aiktcdml.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hosurzsm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2rinoocog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2mszejfqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2pwyecivk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gt2olypgsqr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gt2ghqqxlpl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gt2fgsvwddu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gt2xphlkdfm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2mupqjoev.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2izwtevfy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2kngpomxc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2ikcssmtb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2zoywlvko.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2admpfjch.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2vmmgoudb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2wkklkiuc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2armdbtfm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2dukslugb.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbvtbfwx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2kccwmkmw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2pbzfbzng.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2rozxjfmk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2erudkftu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2jamrbild.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2gjvbkmsb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2reeexdfw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuhajbij.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2htapluor.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2wfjkydcj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2ndxdgiss.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2xmazdjvj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2geonjiex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2yraziefu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2ztwlyvzd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2ippbexkr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2fqmonvxx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2cdmnuukl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2evgzldmm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2pfejcpyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2siahzowr.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmwahggw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqsmujcw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2ndnmnyhl.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2cdsoxpkc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2dazdgjcu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdbmfyeo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2nviswexz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2yhpprfmz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2tioxkdmq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2hegknzcu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2dwksnqzr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2whycocom.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ayhjsxxp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2wzdtdctv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2evhbabfe.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2ovwtkell.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zyxisosy.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzulciui.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gt2zjmcpbtn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2twxlslgc.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2nuhcphzz.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2ljsszdzz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2iidwomqi.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2vumgufqi.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2smjmqxzq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2yphmlbdc.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2dajhmwqk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2agoyhkzq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgsegfpa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gt2eoyckqqx.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suesbpps.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2dqjyfzfm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2adfoyzpd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbgpwwzg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2hfwepnne.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2fupczkmw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gt2ipjjqted.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gt2chnlyxlp.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2xizpjqit.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2xvkhjzqb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2temiarql.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2dppquvbb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2dkprvmwr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gt2hnrxmlgk.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klrneayu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2pekucbhn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2oxebuzrx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gt2yjhgvrnv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2mgjpepyv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2lshzuwkb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2wjhgcqwp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2rdpgugsr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2safqofku.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2opsziaps.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2igkunjnm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2bgsgwoxz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2ppjpodar.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2hssqknqb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2htvcdiva.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2gyaevapn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2eqpfopbq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2dxjwmsqd.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2vvmkryvh.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2hbzfqang.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2ptpzxrdq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2zjpocbtm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2lrmgjxpt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2fwtookge.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gt2prxiebwa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2tdqdnkgc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byxqbcbn.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2cdsnwvng.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2xrbahszi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgfyuopi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2yxjasaxm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2kywyxkcz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2orfcuywn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2dhzqtbyy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2qyqanjpi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2pwcpfpmw.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2ihxuvkts.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gt2qufwakja.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gt2kkiftxdh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2ksjgukyr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2evjezpxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2emubrxaq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gt2qpznoevc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2ypbhnjhl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2yyfjlgqj.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2fotswfbb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2phabsajf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2lgtexezh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2qelmwens.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2bqfihvsi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2iepwrgne.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2mmefptmk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gt2aujjjsam.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2nwbmgrcd.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2jsjaflsp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjrdgkex.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gt2bosmoakh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2yymatmbl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2kbyarqmw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gt2apbujqqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2ppmlgfib.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2mqckxsey.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ztfryvok.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lnexwlhj.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2ehgsmtcy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vblijyjr.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2zxdeisyv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2grpwodwv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2qelpqkvz.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2yjatknje.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2kkiqnfvz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2ejwcflfn.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2wnhxdqhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2tmdwnkdm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2dcasxngh.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gt2tdgfxxpk.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2vjbldiyy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2xxeigenk.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2rrnqkrzr.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2adbjjela.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2nnxchusv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2xxbfjkgi.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2tggovcxi.html


<!-- 参考信息 -->