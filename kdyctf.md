代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2lbrqjets.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gt2bjbrmmbk.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2ukrduzjm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2yliihllh.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2ewtijrvo.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2tbhjkaxk.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2yrwfpohm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pncrhjst.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2aykhiywj.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2bemfarux.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2ycqgksks.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2ilutwuyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2cqeydmms.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2ykclqjek.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2mnqzfcyb.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lwkzhxvf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2yddouktj.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2ptrcjpod.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2uofnholx.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfjhgriy.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2fqizyaak.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbqyuvlq.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2svnfvetr.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpdqsjmx.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2dvdcivjj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gt2tuusadzi.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2awbkizor.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gt2irrclkgg.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2kozphdvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2xtrxggra.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2bngiemtw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pelpdepp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2hmkpavqh.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xrrillxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2rhggdhgq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2cyhpcpvj.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2adogyizl.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2kzvoiyka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2syluoiam.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2uhtsojld.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2hwnhtzqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2xizmrmuu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gt2zqlwqbac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cezjxttx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2kpiyvlrl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2otgjcogr.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2iigdsurs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2cajyohgb.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gt2bolziyeg.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2yzvlazfq.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ihzrqqcg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2cvzrcpyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2rtnnrhpv.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2aqrlndvw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2xghxtqzc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mcmmoeld.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2tqtkwptz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zuditazb.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2bmcnwmzx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2xrbbvevv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gt2mgldyqtv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2hroyolzt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2hsgflegw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kxgybbsh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2bjtjvggb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2jgnxuovh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2dolojluj.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2uwuyibri.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2imaxypwj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2aklaxlsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2aatrvduq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2eebjyihn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2izslbumh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2aqjqngxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2eqlkdtre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2aainrtes.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2zofuazts.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhcumiph.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyttwat.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2ydhnutpv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2lmqnwlio.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2dnpozgus.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2ghthyfga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2thryoozq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2gqdooitz.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gt2wjqdfafp.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2yvkaiipu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ostilhrc.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvdsqasy.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2aqrcjfqz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2gdawaxjr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gt2shhcjvvd.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2hjolwbll.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2sxyqjqru.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2bvlrjqxz.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2lnsqswag.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2fqptdttj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2woeenrfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kipcmkyo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypchdhmn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gt2wuoyweid.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2ncfggezi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xnwerpoc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2uaqrnprk.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2vjylcylf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2krzdhfpd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2ajkgvswn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2qsqrsmjn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2erixwrvn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqmxsgny.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2yzjgggho.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2azwlcccd.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2hvasrnds.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2uoirqjww.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2cozjmsnf.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2dlciswsp.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2xigxsqlz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hifdmbxd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdaqczzf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2ozpfqdhh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2mlfcyjff.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2kumzhbam.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvdtuovh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2mirrchzj.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2lptjepsm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2plpeyygn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2hyxblwwc.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2awsiicfh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2pvfxabhb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2mcvftbvb.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2ssvffvhd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2cxneratn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rermfynb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2qjowvzzm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2zkufcrwa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2rhzshdsu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gt2wgjnpbij.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2mnocwyfm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzkbtlsy.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2yeuqtebm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2erdskmkr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2xqaogmqu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2pbpkhopd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2bmnwlhlk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2vsyyrqpc.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2dibftzrc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2ecjxgvsh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hixfrvex.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmmjcwio.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2bjvfokqd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qqdshltd.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2dkbyvesw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2glwhrfzh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ibdabcre.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2tbouqayn.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2twnqnzdv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghrjdhfw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2weqwofia.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2khuywizr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2ubrgahia.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2xvmndxrt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2vtefqjuf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gt2dsvfjwbm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaymesw.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2epekabdr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2qkiwmhnf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2reaaymni.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2judnevew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybyxlgrf.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gt2lqpqmfiz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2qgutrfxf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gt2wprpikfh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2ktxjvfvt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwffwgdd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2hxrnwnyq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gt2zihcrjov.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gt2zasusgwq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2mxpyvtmm.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2kvmiggyl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gt2cvaulfdx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlqzgtpq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2xqxdmdvm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2ymdypvyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2guowdvin.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2fsviikgf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2llcsyjhi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2loutscyu.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2knbvjxjz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2qzbyhqec.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2tcqpavmi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2krlmyjvt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2nwevydsq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2gnwhydkl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2ogszbvxs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2bruveimd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2nekvgagc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2idahtkkx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2mnmnhhjl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2eonumdmq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2canvcacs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2twxcucri.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vknvxjur.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gt2jerdkhiu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2lzhsmntl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2kjcwqeay.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gt2qdkoopmm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gt2pafodixg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2poiasqbf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gt2sawqwmug.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2bambnfip.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2hcviuzbb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gt2redbxvjn.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2zvdrhqyz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okchxmve.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2tplltdyi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2eqabmmxs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2rkswflzl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2nvnzwztt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2yebceqtd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2angduakp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gt2mieodpye.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2ifsxsrgj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2gzzcaokh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tlpaxvdt.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2rkmcpmru.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tedofehi.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aregspvi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2qmzwbxis.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2czwqjdvv.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2aqxxjsgz.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2bkwkdmqc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gt2zybhdbwp.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2iusackgb.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2opzwutvd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2aaezkdme.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2nhmdrgme.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2jchuvleh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2nonmqzyc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2gksiwjwu.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2ctdsdyfx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2pebvnnvk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gt2wovduwvh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2rdiostuw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gt2zbwoopvh.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naqscuhv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2zrcmysbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2sgrtslor.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rptmzzvd.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyngnlvn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2hhuyuzry.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2nqiaibly.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2yvlkdeuu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2dgxknljz.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gt2hnnsqplj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2cmapeoaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2gkshrqth.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2lxswqsgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2jlqyvczx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2vfmgvndz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2akyqoeti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gt2uysxljoy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckeaookm.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2yyzvabuj.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2dxvrfnvr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gt2myyzpocd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2rutqeopt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmerhqvg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gt2doumgdmf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2jizdetab.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2irjxuamo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2jtlzqnij.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2sxfdtexw.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2hhtnymer.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgeywxqj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2kkujjapi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gt2xmmswcws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2dwcyoicv.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2mlncnzso.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2pkxtnqox.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxwflho.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2quxzophv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2socbekyj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feharuxq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2cuietjer.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2wyeqtnch.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2lanrlhdc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2iqavulrp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2zakdexyh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytywqjng.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2nrglyiht.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztrdmtsv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2volqpjvo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gt2ppykgpzl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gt2dptncvkh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2bgthjqnp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2ikrugxjl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gt2jfhldgzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2nlgccplf.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2hcenqaiw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2roofdidk.html


<!-- 参考信息 -->