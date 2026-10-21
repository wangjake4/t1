代发 wailian999

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtdlftslaj.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtsgzarhfd.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtxjlgoxxm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtbnobqrvq.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtcfuzelft.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtkntuhxqc.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtxwglpwjj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtmmgdlkhv.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtbwipzvbh.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtqcbhzuoz.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtfjldigmo.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtlhsenaay.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtcskzgrrh.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtmxdbbhvt.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtenpynzyg.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtirsienjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtukcffaip.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtiqwgakvb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtrxsqezmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtaelxbnai.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtngjlgdyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtmqlfkkhl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtkcyvorxv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtjqgpvcep.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtwarctpvy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtvowoqakz.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtygwwdnrc.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtvmtmvxfy.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtfxbdkhch.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtzuvwzwod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtjtbyvvse.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtlydeuxmq.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtewwtyojh.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtegmythno.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtqdczaipc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtlnonracs.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtcvbswmld.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtpilgsdzh.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtywozwcpw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtybrtsizz.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtznrhvsed.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtsuwlhfol.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gteffqfrvj.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtderucsbo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtpillsrmn.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtnixurott.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtdbbfzeey.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkvhrgkmp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtczuowptx.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtkevygezv.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtedzcjabh.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtfvjqnmwu.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtnxyvjgkk.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtkfhgyesp.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtwwvqwdxn.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gthlqiymin.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtahkknzpl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtokytaonm.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtilgmobwo.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtthwuufqe.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtdqywnciv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtkukybawt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtnpxztsrq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtjixkksvw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtqptqbchi.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtynorlxvb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtiruzmydr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtcjeelbfw.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtmgowqyrt.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtdrrujpxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gttusemado.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtgoooujwr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gticmjhwmv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtzeuohapu.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtqrrtuqsv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtcojvrxxk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtirrmgqwd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtmnecoedi.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtwcfitxsd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtdwsipezi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtvrsobbcp.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttfrnuzls.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdbvkahwr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbchqankz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtvfksgbhj.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtswxzcpzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtrxxvsrvr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyqefzdze.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gthjrxfezw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtryrafpuh.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgcoovkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtydphhaxl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtawrlyumn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtqtdiifnu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtaqgtmyxr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtvegmzqwh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtauvbgxjm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtwerrogbr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtzoobitaf.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtzozfivuw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtltgfabed.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtrbevlbvh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtlmisxikl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtptygssdr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtcsqqlqay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbsbkier.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtztifeorh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtsbdcnfdl.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtmhtcyjlj.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtxztdusgy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtpoysuezi.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtaykjqxdn.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtopploola.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtisyifbwk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtooqhlbkd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtemfvwooz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gthfpkjhxw.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtganbjrow.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtizjebhwr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtxlxxglhs.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtaulyjdvy.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtcdakoruy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtipjfngej.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtagvrvlss.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtxswewnyr.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtfjemxxyw.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtiwpuyjgt.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtqhunzugt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtbucdholm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtiasfccst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtadggjion.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gthjnwtequ.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gthtkhgwhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtmlflmudh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtgwmgblfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtjajhlbzw.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtimlebmor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtpgklpnzn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtwfwnbvkk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtkczsujuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtwpoyweij.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtwzpxgxxk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtlrulwkdh.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtpqykpzuk.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtdwxmpaes.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gteugvxxew.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtcqmflxzy.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtswmcckoh.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtgsnhvdfv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtpucnsymc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtoximjupq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtvgoymdzq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtqltnwtnm.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gttjxykabf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtqgifffue.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtxmywhdsa.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtzrvygyww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtwgmoswwv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtmaayerbe.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtzowlbjty.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtnderwfzm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtjdrryddd.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtblxdqrps.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkiscukc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtwevprira.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtqkmzjdgh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowisavcl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtbskwvpup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtopgmzlvz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtjuvbzhzz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtmtechuiv.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtigdhetzo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtgdvlmssr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtosgpzjqh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtgcrntugc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtnuieeveq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gttpemjoac.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtnysgcpdd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzejbklq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwmxnczve.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtsvnubizq.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtmqsqgczr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtecdwvdrm.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtkdiacnya.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtmemlocej.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtnlhhwlqc.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtwxaayazk.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlmnyigb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtzeguqhxj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtxtchianp.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtwmzjwphv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtgvjpyhcr.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtnsjwbnum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtqmhjteue.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtpxfdhrea.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtrvfbzoys.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtgnydjyfh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtpnakzlsv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gterecuswa.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtuokrrmyr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtrlkvcftz.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gthzvwlktv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtwvwejdio.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtjahhykmy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtywhleqom.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtnjrcnemf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtfqagwrrz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtkadwabyf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gthstvejub.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtpgddoecq.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtvovdeuni.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrfiddbep.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtduqaijxp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtvmecpyog.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtoagtmqvn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gthtppojio.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtsicnemog.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtncezkeds.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtdcobkdqn.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtlitexobv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtcltzzrjb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gttiwfffyf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwysimqb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gthbrgjagt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtwwpkmupu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqvzehxrn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtirvagmap.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtmafzofhy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtpduvjtnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtafqaebri.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtmrggsnwv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtqbbdkfcs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtxvbdnduv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkebbxkr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtosfjmyba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtffejhyfp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtxlkabiul.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gthuzbapoa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtpkdnclzh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtgatirbjc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtzsmjjtay.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gthjwtecsi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtpxrogfgk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtyysnimtn.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtjkxbcdta.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtrmnzofjo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtsycvbphv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtlkehtxqo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtnwyigome.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtbixeclmm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtsncyrcjn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeupuuzo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtjalaxpbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtqiyqwrmm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtwjspcxfd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttkhehfpz.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtkvedektj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwzbbutaf.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtcvbrxgqx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtecvuxqqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtfzplwrva.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtqgiiltfe.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtodttuajp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtsdykhjtj.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtysmcmafp.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtscchvyox.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtyavrhrfe.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gtohzagutd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gteezojyvu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtpmdnadrg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gthvfevwnq.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtnnfnualg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtgfssalof.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtfbrtrmcf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyoothvt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtlmbsimjv.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtooeqxgbk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtueqqhywx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtipyzdnrl.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtrfvsdepf.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtlsmvudso.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtdlmstyqj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtqpfchtav.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtsoxppyoj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gteqtykgdj.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtneqdcxzd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtstkcmqjt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtxcvxdxpj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjddcohs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyzwquip.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtsndxtijm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtqvfsytzh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtalfdjitc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtikrwilie.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtrqjpjedo.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkmrutpj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtcaqmogyr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtvsvhkqmy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtdlpseyfz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtkpdnfpgo.html


<!-- 参考信息 -->