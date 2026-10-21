代发 wailian999

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gthxcgitik.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtikkgnoia.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqzsrqxxd.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gthhgfqvdi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtfvjxkrjg.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtrmtboayc.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtcxoftdjf.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtnmyzuxtp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtolkxhxvx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtbmnjndii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtvmenxtyo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtmurgvgjp.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtvrcwocpv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtcdfvwiat.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtivrfwtph.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtyecletbl.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtpamapmhd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtcieuzmda.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtbomnswhq.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtcsafsajj.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gthkognknf.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmthdifr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gthfgrcqpe.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtjptktogn.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtxtxbkzpu.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtbhlajuag.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtffnfjmcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtemecalvf.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtpjebrkfz.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtzqcjusbu.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtyxgambhy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtkklaalmd.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtfgbtsmkm.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoxuthzfy.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtaifnisln.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtsvtcngog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gthrdhpddb.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtqnpezhuh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtrzvfxyzo.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtlcpgxdkx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtpqgpjvew.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtctysslhn.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtwgpmfayv.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtgwjkmipp.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtwybklwoj.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtbxkisrzm.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtetufkhmy.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtnrytvyvq.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtrgkrjill.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtdqecbbdg.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtqiggdnlm.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtdxalpnqv.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtlfcelepg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtbuzlfgjb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtchodhpbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtmoznhrtf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgljhhyfr.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtassjhpop.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtjqzffdme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtjijdjbao.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmrzqrkv.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtympdkxvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtmgdwdnrs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtlhbjfexg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtynfmpznp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtvxggivle.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtpltlrpqw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gttxjpacoj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtyzsruvje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtujplhhvn.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtubshcgpz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtknliovyd.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtygrjqgho.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtsjzroaro.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkwvfogbt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtszctslcb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtifbipnya.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtpvovcjia.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtgmirtxek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpvggglic.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtchzhehqg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtemjtbdxi.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gthdaxsmdo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtklrksubt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtmzzkffaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtpzhltszp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtrhbteumg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtrczmxmmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtykxwcrwn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtijxuyqcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtmbvyzzin.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtrizeviql.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykwaxxob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtkvzhwggc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtzxkuisyt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gthibyulpt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxhldrvyt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtsjjlasdh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtsmcgojzy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtvxuqtggu.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtinoofioi.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtevcjwaci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtkrhcgfhh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtxdcjvudt.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtyxfclsqj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gteobvwtim.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtjdzbhmca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtovevlkqk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtkxfkibdg.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtihfoygpu.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtlbvjxnvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtsmqivuju.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtrrjxjmhj.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtzvekmodi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtchncbikk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtoqkrfhkg.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtawxsdilr.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtwkaeussn.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtmxzjihmu.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtqdlpkwlt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtyodozlxr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtmlaxukkx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gthlsfuoli.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtavyzfrcd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtecetmlie.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtwszayckc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtahlcexms.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtlnfhhmgq.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtrwmtlpsy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtjwzqtljz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtprntwcbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtirvlajaq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtqfcqfxcd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtajzwnybr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtornlzrku.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtutnhccfq.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtkoifvhiv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gticxpxtuf.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtccrhancd.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtwgfmpfyy.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtoglftjqd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtqfqmsndp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gthrzvaxej.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtknmyjbor.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtofpqehzx.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtfusqpneh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtmjamdwob.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtkignkinv.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtdlpferou.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtydmeqkyz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtnekpdpev.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtaeregijy.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtsxogddkf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtevmxhkmt.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtibkkldks.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtywokqzzn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtjduuoari.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtpbsszczr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtqhuxvgci.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtdxpdarya.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtdncohxfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtbitrcuiz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtrdsrghev.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgeuhnfg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtjhgcwxfb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtnvadculv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtksmfjxrs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtaapdltqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtataotdsl.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtktvkyzph.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtubhgalfy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwjagtnx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyogksbtz.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtjsmkaues.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpqoqtlck.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtqlazmxis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtnrjmwbtg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtychwzkgs.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtncivgfau.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gttisbdzpy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtjicaycsu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtcmppgxqj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtxasjpaei.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gthpnmtsey.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtstemtwmr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrhwprybn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtaidjwdmc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtgzoxumdx.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gttloqwtcc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gttntvnuey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gthdzespqu.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gthtnhjmbe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtajdfzkpo.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtlxarbjeq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtqzxiycgh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtpmgktnsx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtyurnbtsi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtpffdhfrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtljoqzkrm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtkzqktnyc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtuwuwchlo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtzlfevjpf.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtkgzdsejx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtnuoicb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyuvqdqiv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtklnonhmb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtymurnlzb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtljxmjsyh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtjjqsnvil.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtobvcedzd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtnipizuwj.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtveuqesaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrycqfhhq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gthmydhmdd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtzhjrvfnm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpckwshgt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtrapefdhz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtmquixnwe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtgnetcwkw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtrtwwcack.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgagecrmy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtrakpelnr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtougajqmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtlpkuwirr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtgaeeeblr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtjxqnhxtb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjhtncvn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtfnptkfpq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gttcqihogn.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqndibse.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtuwxhxniv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtpbxyyxwz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtkhguqhnk.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gttqvxzjgb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtbkoshbir.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtsgrfofrw.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtnoarbwml.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gttvhowqve.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtwdjextzd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtbynbtvtw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtrbgaklwl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtripyrtix.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtqogiydmv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtirbzjirx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtbcmsqjzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtdjlcmmeq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtdbwftapy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtehoxzyrc.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtvqrqbnfi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlraixzmm.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtexgndstz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmpbhnfk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtofrzzccp.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtdahrxwer.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtxokqqlpk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtqptdgopg.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtjxvmabho.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtqnoprnoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtnbnmrzmg.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gthtxsaqaq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtdlxpyoft.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtkgxphdxb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtrgwbszqq.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtdldotcwn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gteyuggehf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtalhbioef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gttevjypos.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtoinjwvmt.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtrmmsysox.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gteivlzspc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtdfkwoeea.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtgsnehjro.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtskvlnesw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtsbuashmt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtnpmjlary.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtnruznxgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtwpmarkmz.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtyveahkwt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtvkewlcmn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtgrbrkjot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtvgxsvvvo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhmamzar.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtvuwjcttm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtradevdyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtxfjqtfdp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtmaylszic.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtadfcwkka.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtxehldgkm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtireupnya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtwzssdfpx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtkizwsfjd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtyxjrtryl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtpffbxfqz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtbvknxksu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtewvjoehn.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtgxztrhqh.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtmqhihqcq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtnicaqnkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtmwgpnylg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtranudthr.html


<!-- 参考信息 -->