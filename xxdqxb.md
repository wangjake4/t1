代发 wailian999

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtssqjxfjo.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtwwexryiy.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtqxtxbrkr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtjjfdddqz.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtewnbrzpf.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtlumvwrms.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtppqjdmou.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtziulxwfa.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtoyhepgbn.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtecafatcd.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtqxudfhfh.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtesykigjg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtshfugfob.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtklkogxmr.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtpikayecx.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtjwdsfssd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtmqztvfyw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtzaobqvpq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtybcmrjkd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtwbvfufiy.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtiywtoqca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtupmeiqrc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhnvheip.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gttanrwfhg.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtgsyfxjoq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtdrbpvtfq.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtmnzhejqb.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtxhccxcte.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtlpvfzmrg.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtjmayzqvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtoabierjm.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtybkxwgkc.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtfdulfqxg.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtadlbxoay.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtbcgdzhhg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtcvomvajj.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtymjyyqpg.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtaoxrioel.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkrikydxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtqefdreuv.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtsilyvgcy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtwnrwixvv.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gtwkouklno.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtifjcbeaq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtijlluvuu.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvhlkpxsq.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gthkwvamnb.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtrlbtnfgu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtvpagozui.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtlpyymvrg.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtlcnewzaa.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtbwvcspfn.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtxqprfciy.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtmprcjwxo.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtidbqphqj.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtrijwikoi.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtzdrabitn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtcacakunl.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtqovxkiuj.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtyabqjhlt.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gttjzyqfjt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtladzuwok.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtoulmfbrx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtaijdiait.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtwqpaigip.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtnpajkqbb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtdiyopozc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtgrpqkrdl.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtpmpdkeen.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtsgamlzrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtlivfjyja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtvrncmlve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gthitdjitl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtzfpqafdm.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtbxpitxac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtxzozxfyc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtvqnfwsyo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtmyxlzria.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtmidgcnts.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtmcvhipbp.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtgwfgyfkm.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtjprxxgpn.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtzsmtjyfy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtcvnxomkj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtqnqcjypv.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtqeeoblym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtktkylepa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtflkaevsi.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtkwkxxyhl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsghpzpkj.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtgwvgxvnp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtdhyyllov.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdvcvgdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtwmsgoyci.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvqkfyha.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtokhoaxxg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtsyioohob.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtamtxkirk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtlobvxvph.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtseslioqc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtoxbclpga.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtgtdtvayv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtvdjyqnov.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtdhysawwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtcnzskoqr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gttilrwbsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtyitthvnz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamyanoej.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtwldgmnqg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtgjrydsml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtsrrieywm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gturawvkex.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gttwtmndag.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtolsuhacr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtnefsxrak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtvftjwtyl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtbwxaxigp.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtrgvmhfzq.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtltbrlmqc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvgcjmyip.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtmtnuysht.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtmgycefpt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtbdrgutvp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtibwnblsg.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gttvllnptm.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtqahihzga.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtuzueajxt.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtresfjspq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtivusqtcx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtlhhynmfx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmwzksmxh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtcklzwheo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtdkwboaqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtiairyetv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttkuphrgv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gteggmngjj.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtwebdhuqk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtxajhbumw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtakluhojf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gttzlgkwdb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtoijizutc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtqcejlgaw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtfzolwgwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneaqurvo.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtxlxlfkbx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtdobqegwt.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtkykjqyjj.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtzewynrik.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtgvjuwbwn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtwxthzscx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtmlrizseb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtkngpshqk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtysrdsqtz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtxuvfnpxh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtmcmopflf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtricvsknv.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtoxouujne.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtltobeinj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtveeksokl.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtfvmkcjxv.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtsdjvebht.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtkxihwklh.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtaqnvvmjj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtbnpuzbkh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtxfvojisl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtmzcmlkdf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gttrajjaiu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gttzkiphpc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtlmmexowa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtjnxqzhsk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtwjsacglk.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtvopcsavp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtkxixsysp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtctzjiklk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtjpmneveq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtdjkiiftw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtzfukiwtb.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtykcpllrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtjehjamro.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtelgdmoun.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfphyqgph.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtjctkfrwm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgfaboxyy.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtkxbfqeli.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gthcpwbnec.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtwtcywwde.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtwxkhamvb.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gteowyfeik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtoqdhxwnw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtrrdmhmsg.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtveomjkqw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtcvpkpypy.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtcxopjgct.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtemqreriw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtnnvcbqzm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyfqqvxi.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtmfqjcrya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtausddnvq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtxqdmtmlf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtcvandfju.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtsafeypso.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtjpouqqwq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtduhehxch.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtweuksjxd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtjrubqbgn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtuirnzcqi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtcicshwod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtqpoeftut.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtuzojsisz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtcqvpqrlv.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtlzxkqiyk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblzkhrrt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtkacxzlev.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkqbymte.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtoifgmvgo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtupnkflye.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrockpjv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gtjznklhlb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtusakfcnk.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtxtgrezhb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtfgbbzsbn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtttbdtvue.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnvnebds.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtobmfksne.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtzolwavux.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfysklcl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gttkctubgi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtjoxhwzqo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtcwzhfeaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtwzqrfcbu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtjtzxaqjc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtyugahlhv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtvxqlwlmb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttyoihcst.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtizbahqee.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtnzeqwmsh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtwzfkjpoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtppeiciio.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtlxpcbkfa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtagnzevhb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtqewbsfoz.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhrlrvxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtlluhoibw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtciazcqrb.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtmbtxlxon.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtdtkgmarf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtpsgischy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtttsmiatu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghyiffyu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtpwknlodp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtnguojiml.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtlcrhndsa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtyuwvpypv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtjzrdniid.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtxggfxdsg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtybdogbvp.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtautsfsia.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthbajfgui.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtsvihehmr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtwfbhocbl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtdnytrifi.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtyzolrqxa.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtqcucdctx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gthajgttov.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gthkwtzkwp.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtkgfmckxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkujeqyde.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gteouhylrq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtlayofqbg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtymsydefu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtddzosafz.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtiqfvxgpq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtcldnjwlo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtkleesbsv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtdkmwfcrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtnbitvcdy.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtnamkzvou.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtccfsyywv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtsleppcvl.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyppvbao.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtvobvcioc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtewrpkoxo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizouaatd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtpzqcfrys.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtaznfhbrf.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtdgvfdsuk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtxtcfhynq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsdasljv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtqirybnpz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtczsizhxb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtjwuplcdo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtarkooyge.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtpgugktro.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtrhtphbpy.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtqizerruf.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtgeybqvzr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtpyyjbteg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtofxshboz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtarydiwxj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmrvcduq.html


<!-- 参考信息 -->