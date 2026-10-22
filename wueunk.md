代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eczxrhhs.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2lrxatuat.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2grhodnyb.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2zdyaqxaz.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gt2ugfjyoqs.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2wlicsbni.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2mgxsrfuy.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2wwbxxroa.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2luuaaean.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2ioaxhysf.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2onvkcywl.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gt2wvgykaiq.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gt2slrfaipi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsrjozih.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpahyeyx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2mbsbqhwp.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2zclatxzp.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gt2etsrckvs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2jynrrbux.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2cphmdxhb.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2nynayegs.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2knhojjmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2ldwuejlh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gt2yeiblplm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdrjsoql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2pcywsseq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2uqwdefrw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezsdyzyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2wefozaiu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eekanhks.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2fakcdezs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2jgblmyht.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2vizsqvni.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2jogihkrn.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2bdidpnzc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gt2azbdozfn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gt2ddolbfkw.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2pmaputry.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2jyitwztp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kqluxsuz.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmsqtffk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2spujvhpm.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2jgpectaf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2ayrkqusr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpebcyfj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2zfiauhbd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2nnekmohk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2hvtxiczv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gt2apyrqwkc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2yvncgdtp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2zggkbnis.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2wpoejntk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2ojcmwlsb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2csrxagif.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jieuvfqk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwrsgbig.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2psrzcwrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2nnaxjouj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2rlvgsdjg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2lfelqetc.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2fhpskbgu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gt2oalauzbi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2nvxbcluh.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ofcvlsqx.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2qpnwiysg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2utahgdol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2gvpaboxy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2jxijeldx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2ssygzeaf.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2gglwwpej.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2cvozpliw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2inuvmitx.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2rmjkrdpa.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2cetasxyi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2kweoejro.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2ngdlbayd.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2nizocoym.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2evmqluwd.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gt2quhceksc.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2umyueaxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gt2cdukzbsi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2dmlosnkm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2efstmmxx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2yalrpqva.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2bgwqlaqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2jvzhucif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qndlkeig.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2himkybvi.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2lzsfzrrc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2nvqhezgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2nfeqpgzy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2nufjagsf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2vhweaxen.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2twotujmp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egkcapcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2xekvqntk.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2umgsixen.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2jtlajudl.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2clsackea.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2msqlxogq.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnizxqep.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gt2cbnnawxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2ommqaqwv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gt2yfhrbxmn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2cpkrnwbp.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2kvewudll.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2japekuhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gt2uhnbugib.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2plaiuvfr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2kruvvgrb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2hlqnctfa.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2qnfhvzas.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yovlfmeu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2uoajlvim.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2tybredii.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2jocgrzkk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hklgcyhi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2nyzqedwj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfkkfyks.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2ciwscasx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2jgtzybrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2ghltzsyq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gt2hncopjpn.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2ajdksyei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2mgtkxofw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2fxtfaimx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgpfgtzw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2xojzhkox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2zkrdkfzy.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2iqybcejj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2jeghonme.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2pggubatv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uvumoqkx.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxzratoq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2cmnrdxiq.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2gpggjonz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2dpfuxjao.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2ulxtxifz.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2uhwvoeat.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2fhdfqoyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2uuqzeggc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2feersgio.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2ffvoinqx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2ezhurbbl.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymbtpmgq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2rjkimika.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abfxxzdv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inzzavfe.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2tapkluie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2apfuquey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2uukfxsen.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2svjdbzdb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2whxhibob.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfudaqef.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gt2hqderwjj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ievzgpie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2kjqbfsjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2hscwcjyz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2cllafchk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gt2ikrnsszk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2owrbwkki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2vsufdyuy.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2rjnbjcpl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2rtsddoal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2zjgynwsh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odwuhhyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2jrhdvcef.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2awzczlsg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2giaxrgmc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gt2olgnqkti.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2syuvfkgo.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2obbobzba.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2lyuqetcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2zescyzuy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2swchhdlv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2bndebcex.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gt2oaagsyst.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2onniskqo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2zxlsyezs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2ogpxkpml.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2sbavgtvt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwztuhft.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2fsjdbqte.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2dxpishab.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2riilwobx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2adyawqnv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2ruzynnhv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2ydblxsyr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2qmgqqnea.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2qatmyugs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2vbanacjf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2sevfzwpg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2hjnwdpel.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2cnyubjqf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2gibwmzvo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2euitzqqn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2hfpfaomi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2jgebztxs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2oylyvmky.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2ptgtufkf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2eecxirdr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2zsjaxpjj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2okdcpzab.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2zrunqxcl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2gzcgfudg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2ehurljdz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2rcatpalm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mhmvjxdq.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gt2mejlmyze.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2aarpwqxg.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mapdnddf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2hifmofhm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2prkptqqw.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2tokcojgy.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2rbetnvvc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2hxuucpjh.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqcdjmer.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2ekbpqslr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gt2aiadyqir.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2clsonazb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfvlxxoj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdjewdzm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gt2seqeknfc.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gt2cfawpzki.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2ngqouoyl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gt2ajofayqw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2cjymbalf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2rbkdohab.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2erlivijy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2apnxejmt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2rxrqqmyv.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2wivetyuc.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ihuvpplw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2hyxxtulq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2hntrispv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2ljjzwety.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpqtncbz.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gt2txxnqqwt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2rkkeeksw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gt2gmrdhsku.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2lknhivez.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2ldpvxqce.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2qpqqolxe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2vjfqtrzg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2dbglvcnu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2dzfrkwfm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2hntwnnzg.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2bnkolnxk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2ugiaziuk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2vksgydnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2trtshqlu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2tbdhdlwv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pljtoxbv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2cfeohdbi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2fiastosj.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2ehbntona.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gt2jroaymsg.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2fugafslp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2nomgykpl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2lswxmqxu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2wokjattf.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2syhufcgv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2jljrdrgr.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2ootjxbek.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2rqkaecag.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2viazvsrc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2klbtliuz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2wuykimjv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2pafvhrjz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2qyuaebfq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2odwaaqvf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2upzwrkoj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2bmvogscr.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2kxkkshiw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2xarpgijl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gt2razwvoay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gt2kpprfvro.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gt2cxhrwssn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyzluiyz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2busqmrxp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gt2ktgfrask.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2claaxalv.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2nvemuceh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2przedgqf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2vhwmwrma.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2ubqnapei.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlsxmgqz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2xjxjfhpu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2ochtqktr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gt2hskuqzrc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gt2ehdawsem.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2zvalmgzf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2roqhihak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2havupmnc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2fskhgehb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ampiqsbi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2troswqyy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gt2rkndtlwz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gt2jldxjszf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2mxflpkvt.html


<!-- 参考信息 -->