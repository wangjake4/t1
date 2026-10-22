代发 wailian999

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtilggwfnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtstvrwpha.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmkvjhzs.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtfwnnlqbv.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gthgerpnqt.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtcxutggcx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtywilvxiz.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtrsbckcww.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtjuuhques.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtqakfgrtq.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtehiwpsxl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtsqkdtqff.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtjovojbsj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtgxhimzez.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtvbtyhieg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtaastxjrx.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtqmegbrza.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtnwscalpo.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtuztdfahp.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtdptuxxen.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjkhosxf.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtmbjkapma.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gttyspgdmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtghtcwskm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtmbprzedv.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcrzpsteq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtrbpktwfm.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtmsccxhlz.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gtxrmqalku.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfbyuldz.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtapbzgtzq.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtvcnkqjlg.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtjuztkdew.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtgtcsiyuu.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtfjspqvej.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtuoxygadj.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtvhphlccy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjkrnygw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpwnwbih.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtituhpceh.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtcuohnrep.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtutgysznq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtrfxjyenp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopnrdvsy.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtjtzizprc.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtsbfdfodh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gthltzqqij.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtwxzvyere.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtlmwujkjm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gthomxchgs.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtflfcvvix.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtjvezfuls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtufgpxcct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtbxygwdbv.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtdlmcnvqb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtiegeytly.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtifejgxlx.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtinyllmjm.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmvkpoxby.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtnplzprwp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtiqvgnojm.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtxldwdqwu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtjitqjoki.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoxowmoha.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtvjiumebn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxuwhvqax.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtkaazvaon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpbbgntn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtbcpvvuzf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtfirmduwd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtvjdoidwe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtacueghmr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtovfmnkuq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtxdqoykyc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnjfaoghv.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtltxxzknk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpcabhah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtfatreowc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtwmfprzmb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtswcxrwqq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtfetxizrh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtebqvrgxb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtsumswrou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpkolkicg.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtckijgshu.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtlrxevtvf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtmsdogaxf.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtakviivrz.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtbskwoioo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtcjxogubj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtzhmhuckv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtcsxzvlbu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtsycxnuoz.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtjrkmtqgb.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtfkuzkqsm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjshhyt.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gteimncyib.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtonhmvsth.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtndcsuzkm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtyibkcwck.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapnovaws.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtzojhgbvm.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtvgtrdihq.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtogitbewh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtrmdoeqby.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbejcizt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gteypdxfrr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtycvdojrq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtpipysalf.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtxjsqinll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtntndnklm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtbbbqyirn.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtyfcxotcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtnnldwoeo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtixyeuesk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtuwmletmw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtlhzzgbbb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtyjxidojj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtyhgeqlqn.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gthpsmuuuk.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtsnqhoycx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtqhoefwxe.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtefiwjmty.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtszciuwgy.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtiyoelxco.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtkjbdcppu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtvtddkvqp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtndrtfpgk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsxlpmqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtoujvnlex.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnkkrpis.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtlppcsiuz.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtrkowmggd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtcrxnbxle.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtswdwrxyj.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtthbhgwbz.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtblrupass.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbsyxopy.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtfxyjdfjv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtlcyxybud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtmzpuxrju.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtzqvtkztv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtkbretgas.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtjxzeynjk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtaisaenie.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtjfxgaxny.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtmoizaprh.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtofueieof.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtlkapesit.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtfdppaidx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtixtffpqi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtelofrtrs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtoqrfsjhk.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtvvkhgrtx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtdvyqpxmy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtqiqbbboe.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtffctxkae.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtfmuyytxp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuqerbbdv.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqexsapky.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtrftnriwh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtiwundfsj.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxntfmoyd.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbivcbykz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtozjtvnce.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakurqrqz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtssqcnuxx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtsywvfrxt.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtumriqqwg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtburnysba.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtaojpzzmw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtmqsnsgvw.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtfubcofhf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtamungdaf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtztavbmiq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtrazpwxzr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtbzwakuyp.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtvfowcvcr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtqfwmprcd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtkmuxplcx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtvtmzwfkf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtfwxbuass.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdwjmntxx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtcthbqkmq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtsxgiiaqd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtfmqfumkb.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtpwicxsey.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtgyvzullw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtwowhcbfu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwphiugl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtztxapdgg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtfmqdxnkc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtlkwdsgth.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtzyigajcq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtokejcrkn.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtotbvjtwx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtphnolmwo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtebwnwaxg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtebzatfxk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtxjmjgdsn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtnbrmahsp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtxbdynwha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtllhpnrwm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gtkodhmcir.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtdhzdygel.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtmtnclpby.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtyijaswic.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtgvmdjedg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtcswbzexe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhkagcdf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtebycuiix.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtehpcpepr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtyvtsevyl.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtifeqoiyz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtapmuaxbl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtovhejwji.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtxpuoinob.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtnayazgfr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gthtlblapi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtfswclflx.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtoifgsqje.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtphudkfhc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtzglqixmh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtmcapqnxt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtahpozvyh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtlqrtybhp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfdnytql.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtqztzgpyo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtrzknarwg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtcxphlzng.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtpffzjdiv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmffkmdgf.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtolnfcgas.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtckunqttg.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdbnrdah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtthtzxvrh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtidwmrptu.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtoelvsxte.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtimbzxvkd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtlphesvom.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtgcgyjpkc.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtysewrdbu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtcrtcnyew.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtayrmooyx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtnvdjckun.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtaydfnoak.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtkjbomxad.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtwdieiucf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtbtkfhmcq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtlbvdwznk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gttcpgojkb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtsimljgri.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlcrsfrb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtvvyxvtlj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gtghuexjqp.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtogaysjyg.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtpjtibwty.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtjmtodlpy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gteqqdzopa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxvxkfyz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gthwegankv.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtsieojwid.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtagnunffg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gthqhozsrn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gttejfyvfw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtqaszmrke.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtxzupsenc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwbzvtz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlneftwpn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtmbdpdyob.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtswtrrico.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtcmadfibz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteltwuvuj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtnebjmrnk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaowpfmj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtmidekdvx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtklbduklu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyimjiwfh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtorpmqkuh.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtqkzfmlzs.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtlyeutioy.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtrdqamedw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtdnqfwgwi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtcohoxsuy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtnghihyvm.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtspowvyti.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gthslguizy.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdeqbknz.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtreqnraoe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpchcsja.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtxwnizwrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtjdycnapq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtfgofdbjg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtdgipfohm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtabazbmjr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtfqerwjij.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtlgbdiyff.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtkjcvrwbg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtkccprqmb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtecaptjzh.html


<!-- 参考信息 -->