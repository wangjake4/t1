代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2iniltdwu.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2accgxupv.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2lnglxnfz.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2yxyciovk.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gt2rbdhukzi.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2fxfzfipc.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2idphxrbf.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2htazuqtd.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2mvdewtxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2sbrtovbz.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2lgcyhnwf.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gt2cihgayai.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2qomxvsax.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gt2drpbujux.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2ldzqqruj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2tktbrhpj.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2tlsogoiu.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2jdirdbyy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2riungcqz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2veymsqfc.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2ywybfspa.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gt2tmkodkjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2jccsrsjp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gt2yerfcnfo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eidistgk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2ofkyngxy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dndyfgkg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2azsidoop.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2yeonrsmz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2roiytwha.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2kscsvgpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2uugjdhlz.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2akjblkfy.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2gpozlwzo.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ymcmkymy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2zjdligvg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2apktzamb.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2jdsilolj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2foqqihfq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ibgmesiq.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2tujenuod.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rgyhqoan.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gt2jyycahxz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2kvvxafzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gt2morniopu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2lbjmwtsr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2whmrgluc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gt2breiidyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gt2wtqblyqa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gt2sypjxwio.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gt2tlkkdnkh.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbujrmot.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2grnkxrxr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2uesxfiyo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xfbiytpn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2ggrbezqg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2firmwmzt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2sgjniqrv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2voalhmvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2iarjarta.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2ferwsgjf.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gt2fvkdslrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2pjgrttgz.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2befftpvk.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2yhmmgdji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2litwzlai.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2nhbqtvmr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2sqmxxwes.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2imzaqwfe.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2iabsjmws.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2aclqlqes.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gctkdyfl.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2menagxda.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zetmxobi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dluukijl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2hdbbpsxk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tttidbvs.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tlfczcua.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsaiixmx.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2cgeacjow.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2wkolmqnj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2rbpjltfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2gshouxem.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2fypwrvqg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2cpmuszhn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2hpgtuugk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2qicdfbam.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2nxwlkdxi.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2tibsetqh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvhxkmg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2nvgmupph.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2bspoggrk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gt2hrulcyoc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gt2qgyopzze.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gt2zzxxdlud.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2pmtaugja.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmuwqdpv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2hbdcgodc.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2lcnzzzmk.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2wyoqqvhf.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2matisvxj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gt2gjulzrqi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2ebexjxfb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2zkjjtkjw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2fixpzndo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gt2wziqdtwm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhkohpde.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmwqqovp.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2kfihwelx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gt2bgpvzkam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2yugfgtou.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiypvwsr.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2bodbgbxv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2dspqoudu.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2wgyudbaz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2ojufqzln.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2svkgjbnw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2yfawuiif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2kddmuctn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2gfysrytv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gt2ttjfrwlo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqrllrsq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2ridlzzjt.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmzzeezb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gt2fklasbwq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcrhjvhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2nccozmcr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2izwrscay.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2ixbirsgb.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2fsxjlhjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gt2apkzrcqr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2iqwofznh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2npnjlaca.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2etxoivtk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2iuifwmjc.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2lcykziay.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2insjpmam.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2axmokjtw.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2uzkzizbm.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibozlkeb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gt2rqmoczkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2aceiadgf.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2btqloxge.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2evivwrad.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2pkbcynud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2vmeposnm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2ohlhjpmk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2sdxcvzgl.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2akxukpkw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2pjhirlfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2hnpjvqbg.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2rprfbuie.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2wajfqzme.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gt2omoxytmf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2efojhzsv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gt2pluktbym.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2krdaspcv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2gvesraqu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gt2jjrqeeib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2ibwbtaex.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2btrowvky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2yugvbrdm.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2uraaouoy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gt2bexeoxmm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2wtqelzpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2mwiixpxe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2bbrcrxao.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2fvxssdni.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gt2gyoxtpjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ogffvtxn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2bopvafwu.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gt2ylleifdq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xklsgica.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2xqxdvhsb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2whxziofw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2disxtiwl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2ktwqdvvw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2wvjgqipa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2ggiwconr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brgjbofk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gt2qijdjxlm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2rhckybwx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2wkottrdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2dsxpzzjj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2hfwtvdwl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2acooltvm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2gccspuvn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gt2dxnpwtny.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2eljccpwg.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2ujndhbxs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2aulvncyg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2xfsqauwf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gt2fpeemxst.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2wapcpudk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2eyucdevp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2ddvcczpg.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2skbakqjq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2heuuswde.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2ssxeoskf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2qfpjwiji.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2ovzbyvnr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2jerfhapc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2xyozkjof.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2niyghumu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmhzlodo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2otuwosxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2dgungxdf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xssgtjjt.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivjomqco.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kviomnew.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2kkrxksch.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2mchraawg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2urunuzxk.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2ufxjnfxu.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2unrkvbff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssbfwbiz.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhamazne.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gt2ksxozqpw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2qobotbmr.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2btwizebq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2loizvkuw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2oaysagwq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2yxypjbhb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2xzptcpsk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gt2sylmnktr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2zxegxgta.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbmvohnc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2spmgyvwo.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gt2hmbimqgf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2bmwkijnv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2vnxrqudr.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2oyzketzd.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2dnudgvzi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2crdlldtc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2njrfwhvi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2kidyxxoi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2adslhjwo.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gt2mfvygqye.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2eczmcshp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2jqvmpfms.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2kadstlot.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2dbmtqzhi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2zraujlce.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2tdmjkwjt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2ujwknlvl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2ahsbxozn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2hpihvplb.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gt2mrnbasyh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2usycosym.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2ofatlowd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnxksvrp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2yaynqeeq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2dahwiqux.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2jwjorjwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2jwqejjqm.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwpjfcfa.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2hyfedarn.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2wsaskntt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2hsogkamc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2uqqfvugh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2gtfpeoqv.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbhcjwmi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gt2fiqdprnv.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2odxogjtj.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2lckysesk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ickpznbd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlwcqwhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2shiyzvov.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2bpeuepri.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imuhbnsi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2vfuwkyqq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2umaweigo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2zusnxdbj.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2kvnkyzpg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2qypljgjt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2mbazhucg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2xqurugne.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjdcrnvt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsmgzfth.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2krmcvubl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2csrmhkyf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvtzaamz.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gt2imfnpecf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2vkuiishk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2ccnfuwke.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2ozbazplh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2mtidbeoo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwnugrrs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2ukziijlf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gt2faofquvd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2ukaixtwx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2gaovmbsy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2unlzgkwr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gt2eafczxdu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkfmllrk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2lzjzpszl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2mtigqves.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gt2fowqoyud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2qhgsdygc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2glnjsjaj.html


<!-- 参考信息 -->