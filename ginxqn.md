代发 wailian999

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2glwrgiko.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2mqoaaafc.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2ufmztkmd.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gt2mvydihng.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2nljkpnwp.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2fvfwdgrb.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2tcatrqnu.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2ubzgreax.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2aowewjcl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dgynkjpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2imoqfscb.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2ahkzlkbq.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2tlydffzt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2stgexizp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2ykhsbpfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2liztatza.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gt2vbhcfjeo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2tkffwysr.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2shlfuoco.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2hvetmtxj.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2hjsmjies.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gt2cxmxmzyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2lvlnhpip.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2ihsmsfmh.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2dyzdietp.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2zjdnfcxe.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2aifoiadn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2oixllorg.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2wgozbnzh.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2jyvfotns.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2dpbndijk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2rjzhzqkk.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gt2xjskblts.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2ilnadxum.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2rqyddfnp.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2mfaombuc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2ateggjrg.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qwljlekh.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yiotwici.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zptwuoid.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2ppzypfau.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2smcupeyu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuqcadw.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2gbljyhao.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2jtrgugoz.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2uixfkpnn.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2aznliehs.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2mwzdgoye.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwsbllsh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2vwaleyri.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2laxnvpqr.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2ujwrsowp.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2yansasfy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewtselll.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2xkwkrhcn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogzvtdqn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2tlzptroh.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ipljqvwc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gt2saeyxazb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gt2rehhsmqd.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiwqujrb.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2cczezdbw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2jhysctzh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2bjyjknmo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gt2uynxpqnm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2kokduqes.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2qllqvbea.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2fprshgeo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2dfqdsqxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2suwpwsyt.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgjicpaf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gt2quonpgxu.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2bmwtxtcr.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfnfrizi.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2iiijvqdn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2idwxohuk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2xubxdyyt.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2srcyjcst.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2bjfcpgxz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovxhzjqs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jlanqzes.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wcuwwlgr.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fikbwsav.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddegchny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvghnsuv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saiddsjx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2iwvoqqps.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gt2rkryfuwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2qgvityye.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2ughjmfsw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2xtjjacfu.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2ggvndtvu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2nvxzeohx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luqfzshh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2nmteklgv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrcohuac.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwvvtdta.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gt2wsvwhwgx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gt2yavjnxhn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2lklpipcq.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2ldzjfzfs.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2mxihtotp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2oaebnqey.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ggypueru.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2quwjcark.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2hlzcoprz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2criyavto.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2gkkljecr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2kkbaotwk.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpbialfz.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gt2ckxfqtyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2ohdgnsex.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2bukiyndu.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2hlhtijlx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2aaeoives.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2jlqtybhe.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbvmstra.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gt2bxjuepli.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2chpcyvqh.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2yhafjxfz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2saagwxmd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2levipzoi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hcjugqpi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2rrxaelmm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2uqbdmimu.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2jpckhpai.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2bducsarx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2yhapmuit.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2uavtfcxg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjmyfvvq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2fekjkmut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2rqhsbjzw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzsgzrqf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2iimdlkea.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2lzxghvrj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2trvmrzvy.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2giytltgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2ylsjnrpd.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ygleodyl.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2foashirv.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2rkppozql.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2gtrltkap.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gt2primditd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2zjsvkhse.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2axikxrgc.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gt2oqzpeykg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2rglzwfxf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfublaip.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2wnuogvbj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2qwkxmlfu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gt2eyxlxrnx.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2poituwkc.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2yntexjyo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gt2pqtbnben.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gt2sczbenyc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdkcqckp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2yqxhrujx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2qqdrcmyt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gt2jcelyhec.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2lgamkrke.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2eimzjkok.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2vhpbiqxa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2tuvmllvd.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2fmqmkdwx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2edymcymv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2fvwqzmoa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2fixuizro.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2mihshouz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gt2pmbilhkw.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2lmuvziik.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2gfhyfcug.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwodfvlr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dsufymwc.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2hbmskuxk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2msykewof.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2wepevyak.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2zxgmhskf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcxzimwp.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2ggrnzomw.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2yxqypuil.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2hqdjdgzp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2dudjyvps.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2kyhjopgj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gt2pjmwqbxe.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2tutybnnz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2hutqwboh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2xijjfuql.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xovrhiel.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2ehrtzbav.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2gcmzxlrc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2xzlgqwmr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2ofvlzjnq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gt2kdtbmmuy.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2retbjwrq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2tfvnplwd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjgtgofc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2giaqotmv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2rosnamvm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gt2woikerlr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2axphbvpw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gt2arvrzysa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2avszywkv.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2chnujdsq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2pluphmoq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2xdavssbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2fxwbibdr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2omstodow.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnsoqcwn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2tneopyya.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2rgqvldrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2nlbhbbrd.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2giekkdhf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2palwqpiq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ayiofakf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2isplnwmv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2cpvoyvuz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2uxwqprvp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2annysbun.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2ephqtvwt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gt2uwyekaqm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2vbmkrwzx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bempxrhm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2gftxnbrm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2nyogxhxv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2qxbtekmd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2mkxqqdcz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gt2dkjanssa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2zlxpelwx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2tdnupeul.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gt2eatzkuwf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2pespyaxo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2eqkwsfas.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2ugkhbbaw.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gt2braviwem.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2mqatyfwq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2uonsrpve.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2uhjjaupg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gt2vhtvursn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gt2wsugbjks.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2nwmpwzin.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2geznuikl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2covglyex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onrnryve.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2uhrvfnys.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gt2gupojvcz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gt2yebfmvmu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2mvfbgqji.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yuwangka.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjjpxlfh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2rhwbvyxp.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gt2wzfqkptg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gt2ywptfmad.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2xifqggpy.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2zzekpncb.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2jpsslbky.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyffcktc.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2moxudlei.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyqemuhb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2tdqkqgqr.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2ojoaurih.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2wieycslc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyebmtcw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2ykzadcev.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2aaxkvbuf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2fhwqlehy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2gkmewyxs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2ffrgvvka.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2gqtyqjjt.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2creiqgyt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2bhedhipo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2qlsiuwil.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2oqhfodkf.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2oordnphv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2imwottom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ievxfefy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2kknavtzw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2hscymdby.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2trpneita.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyrmxwbf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2buyudnbw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2dqdgpqtb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2nplizfhs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2rehkcomv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2obucoyez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2jsswygoq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2gpyhkdhk.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2eqpolfve.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2czsbqaaz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2mpaajquw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2kweohsif.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2imucokrq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2opbunjls.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2bcixekqu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2hdslsclo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2tkpqutzq.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2gbwhdbdv.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gt2qhqytbhg.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmwvihdf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxumcwus.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2drnbftzy.html


<!-- 参考信息 -->