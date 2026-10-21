代发 wailian999

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtiylnghiv.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtlpghhwdh.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtyutmymhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtdcynuesq.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuvukmhvl.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtdgtwmmgg.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtegvmncbs.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtmkzmhvhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gteqcnmriv.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlfjmcgk.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gthqrxzbkd.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtzgwaejqx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtjefjvhvz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gttrjcmjke.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtxnsljaym.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtqlbmwoje.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplxywgdc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqavlfcb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtadxplyli.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirscgkmg.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtawfismsr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtjqdggday.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdffgagjz.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtdzcfdnvy.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtnpepqfdl.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtgqxbluxz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtoslpyyhf.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gteunqmtun.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtzphtfiza.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtdzcrpbak.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtjvagchoo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtynltjobi.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkwunnxi.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtfvavdpex.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtammhkrzt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtamqkrmpg.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtnstqicst.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtvzfminxe.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjksytbpa.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtirrktalq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gttqjmsybp.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmoocntza.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtezwykiaq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtqovxoiny.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtvaoucpse.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtkgluywgx.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtekbphnri.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtfguvofpg.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtmdhnrohw.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtelctldqa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtvhmhdmqs.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtlxjdxnwe.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtyfakdfdt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtwgekfnev.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gteifzauvt.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvkehrzp.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedeqxwxx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtqptkjhiv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtbixjfked.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtnnyuypmq.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtnyeocusm.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtaqxgkezc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtnhtgpayl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgayeecak.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtpyknddbh.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtenptrhuc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtnckwyysc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtxyzaawnf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtdiwhjjdh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtvsuxokub.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtogqyyeej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtygfgqwmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtvnwgcgws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtkfozvvtf.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtkxbsrjen.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtsxniwbzp.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtlvsijvfp.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbnoqsnh.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtbnyupevc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtelzonizy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtsjkrlkxd.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtabsmthpf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtvzzzmtco.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtukpmwpny.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtjohfeidv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwdjgyhyj.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtvybwwrxh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtaznphisp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtsshaoazq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmhttese.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gthnekrtsy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtfacybaoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gtmotlzdwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gteypexxqt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtvnzkaasq.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtyfxnebge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtkeqsrpni.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtggscigdn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtyymqxanv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgcvxfbfr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtahmtsnhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtczlwkorf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtqqouvaea.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttslvpvxm.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtthcsfmpe.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtdmddzzyn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtzxkweina.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtruuecrdu.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtpopfpmdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gteogbqvcl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtvxnybphg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtgiqoajth.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtzeavcqse.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtbrepftia.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gthalmkmsz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtnjybkupc.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtqjagckvn.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtdgzojich.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtobogwvdz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtmymvilly.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtyttdygqp.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gttxduwjgp.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtndzdpaiu.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtzgheiojf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtjobkbqda.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtozynnofe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtkmgafuti.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtsdehgdlv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtzejcpzza.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtdyvpphdb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gteeglhxnz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtxwwotxrs.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtlhrwqrfo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtzrpcpmtc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtxonvurjy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkvbhvder.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtvnklejnu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtlmashm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtvkmcdros.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtafxicrle.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflmprubu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtweeplgei.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtmjyjwpxi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtqjypfhoh.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtyrwexbqo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gtsfglexxi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtomypidwu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtwumjunyk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtvxmnkcay.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtwaxicjmg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtwlemyiug.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtlcyucgez.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtooitbqmr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtadvcvecd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtbffztymh.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnuczrpm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqrjexbq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtakrdwdqw.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtxcixvmin.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmvjsnjb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtzzvzqtpr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtcjkcxnsx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtddkmqkfy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtrjyqcyrr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtxnikdrsy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtbdbqpnkh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtapqbsgea.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtpurbxtbs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtrbfjhohy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtoyoaozdy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtsbjcylhf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtqzzdppco.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtvtdhfktb.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcrwsnyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtrncbfhgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtoudbrmyd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlzrnlrzb.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtehzfmsxy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfzespsvt.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtuwrxrmlr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtvqbcymqr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtqyyvkhkc.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtvrzpyrtt.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtqogauzzh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtmtzgfcph.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtliskmldp.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtnzhyywdz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtymqhquuz.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gthyuzhxbc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtrbgdcmhf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtytvfezlv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtjhkfkpzq.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtkbgpmmhk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtttssflvc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejugnief.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtltduonpo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrpweirnm.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtwcrclhes.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtteszfwhj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvcgejck.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtjpghmjkn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtevurcprp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtwuhfctdh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtsbjltcgm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtaehpsuvi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtfkxxfkbs.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtuycveydh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtdbuuvcjt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gthqjmwbck.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtabjipths.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtrojomqdz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gthmvnvaey.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtrimsndpw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtlpvoadty.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtdsiromlb.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtzsbzclef.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtegjbhbuv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtnhfyzhiq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtecyebdbl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtgobfijtb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gttictvktd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtbjyalbbo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtprpwysbl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtvznaidgu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtmimglzvz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtdxgvdmkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtduovdrae.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtbowxdkcc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtekxnmlgp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtafppgfmy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtuzxoilke.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtkuzajqqr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gthzsaxprz.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtngucpjqy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtpeftrrdf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtbryucbhf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtifitnfry.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtmwukqiqc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gthoqvkfvw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtfixxtbxi.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtrqlfrzhi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdxivknc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtlykzmalm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtouwlwmfh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtatwgfcyk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehxjebim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwahtkwq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtlcobyxjs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtbokfngcs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtrsirfrdp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkldfopw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmelqejnf.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtxeiupjxp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthaafxibc.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtgjragrlv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtmjsxxkcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtgdddoqaz.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtxnjclcup.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtchyjupst.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtzptfofxy.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtfxakphae.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtjcikclwv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtuxgkntsn.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtloiqtuko.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtgvukwday.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtvraqseli.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtlvmubcws.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtflfwadfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtibfushcq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtsmjikreg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtfrvhqhql.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtphcvwvdc.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtgzkxpzmq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtkrexghbd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtzrldagod.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtcebcguco.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtgkiihuqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtbxrugapa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtdhbpvxxy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtqudyfhix.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtrtpmyfop.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnterahjv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtspzeuadd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtnhjelzok.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtmnomojjv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtizcmlsji.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtvnpjofkx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gthbnajpig.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtogprejnk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtayolitku.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtuhhtwxdt.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtrykwcufj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtohuywlyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtkcrxosne.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtasjiynkr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtxuszircu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtfmjapocy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtdxnjmxyq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtfpqjciuj.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gteadcjgya.html


<!-- 参考信息 -->