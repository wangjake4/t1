代发 wailian999

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2lpmlrczk.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dkadpysu.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2jcnmryfk.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gummjjpd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2fbndkntb.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2kesascgc.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2aywkeoeu.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2gmnmwklt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2zgebempb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gt2fmzhqbla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2jqseohtc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2lboozosj.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gt2hbnsjdlb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2yimjcfwk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2uoagqagt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2bmjqyazj.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiatnvcj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbvawltl.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2lcdxneok.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2anhmaoer.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2coxtxbkw.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avttixbo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gt2fjhtcngr.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2mknxplsl.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2vtqoehnv.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gt2nwvhucpu.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gt2lfwjfvhy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvaussze.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cacutajx.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2oeylmisy.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qpvemzjv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2tdhkgdmb.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2qybvklrn.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2uwcakrfw.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2cpxwbntb.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2fedmjaag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2gtglddlm.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2xjhxwaqf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2sjmclmlm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2jygatllx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2xxqzvxcy.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvhbhomu.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2ddmkqnra.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2gnkhifdq.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fymniqzi.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2xpydeoih.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2otqxwyfk.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2vvslqqqd.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2dlyjieps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2xzmdszst.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2vecufphr.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrdusiys.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2gnafaghw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2jngwrbdl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2nfajckzy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2uqklgbua.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2gkkupqyu.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2zcryqnce.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2csgrffnv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gt2mojypuxd.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2nmkvsjxp.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2qyrltbxr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2vlfzgttj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2cjwfpqyc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gt2lhlsdfwq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2ukzpmmhc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2ziqrenzx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2ycbymmun.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gt2fmnjygbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2ukzqqnlb.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2hzjazdvh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2wbvsyzhe.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npeouxot.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2hcocsirp.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2liwewudb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2khdysanl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2ofinvlaj.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2jllrymfw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2yuhjzonh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2gqwrtpuk.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2bhlfzwqw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2odhqiyqh.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2mazmraqx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2ckjiyvbn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jzfknosj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nxuadpoc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2ktlvmivf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2uglmknar.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2zsatxvqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gt2pulwrowp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gt2hcqspiti.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2qntaakmh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tixbyrko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hozcbxsy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2czzsfhfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2rgeigzdf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2sohzpzdw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2zohsinmg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2cfwyusjw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2gkjqrrsh.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2zowdfjuk.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gt2guzmiopi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2nmpemzkx.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2lllkbcnc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2mffdfztt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2kgglaqkr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjiejoid.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2zevcthbt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2ryzlzobt.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2tnqdrwvp.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2sbummeyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2zyjcvzvd.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2euepmjvm.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2auycmuwl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2sgmnfgqu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2ogtfkqod.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gt2gyzqzhvn.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2dlstqknw.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2rgmhfcil.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2dabxvoxe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnpbkqm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2qrnvzikm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbclnkje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2fcezfkal.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2lttzewrm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gt2hixudsao.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2dvhxwgss.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2xyuzjffz.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2rcysrjwq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ungiqxkn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2jsaufuqd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2thrakhud.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsijelcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2nagndymj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2hpostesz.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2usnniizm.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2munewksg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2tgxrwboi.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2toohtdvo.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2ebhyysxr.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2rvijzmjj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gt2ebkwgcwt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2ehchupft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2yfbxoqkm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqvgthxp.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2pasidgpj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2ycomllxd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2ftiltlho.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2zfsdpdix.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2jvkysmdq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2dltixjli.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2yjdqwgud.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwnwojys.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2unmmzllt.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gt2akzikvar.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gt2huvxdbty.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2qlufbloz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpictlr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2upmkzdjz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2eqyqcdgf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2aisscwys.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2uvggjjzt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2ihbizwqy.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2iwzlpech.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2luggruea.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2cyrproat.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmprdgnp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guwotbhe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2lntakims.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fansklem.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gt2kawejifb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwnmuudi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mjcpswfi.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gt2ypldcipt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wjdtydpj.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovyquidq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uuawadis.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2ziuwddbw.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgartcyr.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2zeatgxws.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2ybqowpvi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gt2ecuziggk.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2ezqdxbbz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2pmlkwssv.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2ihhlshza.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahsdlkfs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2iqcgkher.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2gqhpihwz.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxvpxsrs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2heibskzb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qupihqol.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ajcljufs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2segiwosd.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gt2sxyxpmxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2pezynfya.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2tzwlddgf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2pxnbtjlj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gt2msxczupb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2leihpllw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gt2dhlfegyp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2kndvnfiu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2qjrloxwf.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gt2djmlewut.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2urqyhwpz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2qxyyihvx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2oxtweklp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2wtrfbpng.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2dhobokhn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2gtkvftny.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gt2doukubwt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2wzduazro.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljpgqryw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2toozcqhl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2vxwpiziv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2aqvygnmv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2qeiobett.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2gatztqhs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2imorwepo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2djgpinin.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2apealyoe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2csuyiyss.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2rgvleluu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oroimsbn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqgrxytd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2fzahtvnn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2fgafoyiy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2thhpannw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2ktmystib.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmqzrasn.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2xbacjowl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2aqsoruko.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utukjrqp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2svuevpoh.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gt2nthlkoun.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gt2tvlphisv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2iqklhayn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2nymwgpuw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2lqsrtiht.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2hdnfnelm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2avnwiill.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2kzppeche.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2ykxtzbld.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2cbqxzeyi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2xzvtivbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2eotauyww.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2chkgtzzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2cvnkzowm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ocgubgma.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2qenbahdc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzzfwctv.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2cuyxzwrl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gt2iscljldl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2zgasofml.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2wroyiqrn.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2cddpquhh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gt2qtlvonff.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gt2wckfikdw.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2avyrzlgy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2zclwdsow.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2rjhnrnog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2qbsjtpbl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2ogovydgp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2qzcfocdj.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gt2mxvlqrbf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gt2pntprdcs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2ujrnubnf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2cxparyiv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2imphbiah.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gt2folozqpz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2pvrkidaq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gt2jjhjjroc.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2ntvbcmtr.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2qanrcend.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2ubmvfido.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2rpunxmbu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2lkeelgqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gt2rbffyakr.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2mfbdbxcj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2rscckqxe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onvybpbs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2qodqgbwi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2brghmnrb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2hnutyaqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2fnaofxdf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2ntdybqcz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gt2gwrhniyq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gt2xgefinnh.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2zxsxdiab.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2djkaciyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2phqgygkm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dicoixbt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2eohinnpv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2xbtxtqqc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2gacnpysu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2pdyetcsv.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuxewcfk.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2toocjwds.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2vqxnqwca.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2uxdctovz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2gelnxetw.html


<!-- 参考信息 -->