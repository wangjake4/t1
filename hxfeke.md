代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2xpuforyr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2wnvfvgmo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmwxgibc.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2euiwdddj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2mbudjfsv.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2zmlgmpca.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2gftvkktj.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnafrqcm.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2atrhmoul.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llsgabgi.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2oybueljc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2jnprvqkx.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gt2cjusnmrb.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2jqgbvunt.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2umqcmtdx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2owxqtjkp.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2pqyztnff.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2gczwzpib.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2bonbhnif.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucnedaoz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2lbyafvhp.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2udkyszfr.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gt2tgvicsuj.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2holkmwaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2prezimfi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pqgpprvj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvvpzdff.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gt2yquqrzgh.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2njcbmeaj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idqmbqzt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2faemvzdz.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2xglxglil.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2rcrcugci.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2ohwjyora.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2zxtstamd.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2eznukiso.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2ytqudgkl.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2yswoswrd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2dexmafei.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2panrlwse.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2myrhziqc.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2buqkkfvu.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2gukxdewz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2wkigqeld.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2ixwppkbm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2elgausio.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2keqihofa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2serpxujv.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2odhukybu.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yncdzsik.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2jfxtqynr.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2szqfyzbz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2pnktbzyd.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rvjfvmuq.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2zdvvbutu.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ftxglgch.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2lfuepcoo.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gt2ftqweqgb.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2paqqzjwj.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gt2ubtevkmb.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2thoemctm.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2zghjomfp.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2zgdclkib.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2objjctqm.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2xjgbljqp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2drmnxmjp.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2vbxsijac.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ualstrpi.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gt2yjsvmxtp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2njddnofb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gt2ydygettz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2pazxgcnt.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gt2wjbgphix.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lreafsch.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saqwwqby.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2zcdrylbx.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2caagbwbx.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2diomrihd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2lrxqeqor.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zopuoqrt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynrytene.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2moxgpfqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2jmkhidnw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2jfouomdl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2zhmgyjoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2mozkmxmw.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gt2vebpmodl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2iufudceq.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bddowjwy.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vqxrrugi.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2vdqffnwt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qibduskk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdbegepl.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2dinjmuyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqqvtkxf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dsmtayru.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2nowwqejl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ypxwkxrg.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2pjbatnra.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2fckmsuku.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dwdddygd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddfgtf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2yepfeahh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2bleicgen.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2lpqyvpyv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxrkdcfg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdrysove.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2ezxlmbcp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2wxrwdxqh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjrvqsc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2huscurzq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ddnekacz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2fxnuxrfc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2geanljzg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gt2yxvirncl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2slcxqjgp.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gt2xwcxnaaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2txvseysa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2efhmhywm.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ylgbwdbw.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ehwughzp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2edljbuuq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fabqsbmp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2epcsqpgg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2otetosrw.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2cxbxqeqa.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2zpxljzjl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sopregas.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2znltvwxv.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2riggehyt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2qzzloqnu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2gvihdqrz.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2xoujnrqe.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2ttahiblw.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2akykxtnl.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocqshkzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxcsolpj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2fdzwqnsm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ovikmubz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2dontkndq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2awpcshpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2mvednych.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2nmxppiyg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2rhlcetqw.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2lpfbejxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2aivmcxuw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2almtqscb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lglfgnuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqwuiucw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mffpdzit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2quytzjis.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2vhmznubi.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2gspzapgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2szetquta.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2fxgrbjdi.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2ggzoulmc.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2mkclcowp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2sknpslmc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2qihjqutq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxqmhjdn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2hudgfkef.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2ijqskoai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2wnhcnfql.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gt2kqwewpce.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2uqqhppuo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gt2ggeqxbab.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2vzicbcvo.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gt2xpylreim.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gt2lvmsxzqy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2ggtqtnfg.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oczlidgt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2tlelheck.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gt2areokvlm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2wwgmjsup.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2duqseqng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gryfvuvw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2zyulybbg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gt2xxvxemjd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gt2tfdqdmej.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbicigbc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2pxsrdbsv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gt2hvnggsfu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2kldadfbm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2pogxoppj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gt2nkxucedv.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2khhadewe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gt2aykbwqim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2lszfewff.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2udlgsate.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2xuvhngfg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2snijjngl.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2njzdkfpw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qadkqswg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ohmyvawq.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2vmvznfqn.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2ekmjhenx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gt2xijrbxyo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2rgsqkqxa.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2sumzrved.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2kqrosmvk.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2topqvsif.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2hoddwtst.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2szaxeaqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukqoorbg.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2rscruzkq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2hwmnllit.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2rseaatzw.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2ehzwmshf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2yinlxuxa.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2wadyntyk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ggdncpdj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2gsnzzani.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2ddjhrdpp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2iegqvggs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2npzjdplw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2ewpzonmj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gt2drfvjzzz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2kiwervtm.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhqknonv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2jaczpdoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2rtbglixj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ixfrqyra.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2seddkcnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2ggkjajic.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avwrmenb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2gmkpraop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2efwgcvbc.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2iquxycqx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2ibfyekrb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2reygflrl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2gbtyrtcu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2esheqnvt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2crxgctyy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnvwgrl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2xufoqwdg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htlihqwx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2jxdlmdst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2xdpgefky.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2tgfklueb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2ebuecaus.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2pghvhuan.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2joyrjkan.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2ssrxgpmi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2jjssyvzi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2ytghajeh.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2gnvmqaoy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyhkujsm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2kqralwnv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2tyucobdr.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gt2vbionmto.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2bpxwvjtq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2dererymr.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gt2nrsrtpud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2vaovwnvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2cexohfhi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2xlzceopp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuapopx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2rjbvjkky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxfockmz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2ofcknwij.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2bypdfinn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gt2uxengyfn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2qnedrsej.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pkzukafs.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gt2wsenyvys.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otmhrzod.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2qzmvmhqc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gt2vdfluram.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2bbplzhlb.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2gsklysjk.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stuhzszf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2wgehqhgx.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2eccmwpze.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gt2nnvvphbu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2znkiyczc.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2suerbexv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2fcyangub.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2srnqdpph.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2ggjumttl.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fclwsxod.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjayjok.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2bwvosjhh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2njmytdyo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulmrftwk.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2jexucuea.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2rulqzmgi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gt2iexzvpbl.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uawonxbt.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2argietzq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2amxuheeu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2uycdgwoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2nxkqzjul.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2qhealrvp.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2buaubkla.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gt2anskveqw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2vxjluhdc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2xnimcdku.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2zjggmrey.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gt2yeinxglv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2jeqnvueu.html


<!-- 参考信息 -->