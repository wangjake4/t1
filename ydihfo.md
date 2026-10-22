代发 wailian999

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtbhigrfqb.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtllxvtbfi.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtdfxyyvxj.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtguhlbixp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtjnycnoam.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtogsofdto.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtsbmprlhp.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtxtdygitd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtqkjfrvug.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvflbuvn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtjaprbdjr.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtogdkbnsu.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gteljeujlb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtzodnstku.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtsyqarusg.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwvdutcsg.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtgomznjpl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gthpgzlwud.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtytzkmfls.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtxmrepjns.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtqmlxcvjz.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtgpwtsquu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtysyxcqnm.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtnafmelbv.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqroipyn.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtfxvezkah.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtcmfzbpml.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gteradzngo.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmyokqxqv.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtctmtjhyx.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtduqbiaux.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gturadtkkj.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gthsxuaxet.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtsrnqfwku.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtqeoofcmk.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtlekyortq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtqqtdsnhk.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxoaazxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtlmismjqe.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtkppyulmp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtafklanon.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmifbmvqa.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtwstoxjev.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtafxvryko.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtaqtefkgy.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtbsijodbk.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxysukpey.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtripynfvq.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtizrgtwhr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gttewhcrdj.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtkzsmgjtj.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtayqzrmqg.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtogfucdvb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtsarkdbba.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtuijuxnaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtapxyusjj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtgwudbiob.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtpeyjobtf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtoxgjluxc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtwnswomlk.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtqmorhbsp.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtyffpdqps.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtkkkfbqff.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtuafnthoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtyrmbybth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtlklswepe.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtgjzspnrt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtkuqyfaej.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtqbtdqqaz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtaabjiquv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflxrsegp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtnrkqcdor.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtyokxtuam.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtutpsdkdx.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbchdgvlm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtzzhpjgme.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtdtwyzmzo.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtcyhbglpv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gteofyqpfz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqzafuwqj.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtqypwzwid.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtulfsvium.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtucbarkit.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtbogegspi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtewkvryiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtmvtryuyw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtmzomidoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtyfkoubnc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkugzqix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtmkrvhiyl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtnwakbtfh.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtxbswoucb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtaiwtnvhn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtemipwaau.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtmjtunlud.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtxbpuufmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gthdgzzeqz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtibixgsko.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtbfnlgfch.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gttkwemzxp.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtocxifyut.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtokvvumei.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtoesxsxaf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtyszystnf.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnkzukzk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtesayxkbw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtbdsdmszd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtkrjsnnwi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtfjdwpgzc.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtowzjcfts.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtlvqxjswz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwdzoudam.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtcmawzsui.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtlyvfgiwr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtjfutqdgg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gteqzlqzso.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtsojyyjpm.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gtrrwcoyhj.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtamoaucmh.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkyhzawg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtlptrnurs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvbpluebb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtlhglbmwd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlrqmibpg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtjgvlnmxi.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gttozbctbs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtbxbqufni.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtsfsdbmfg.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtyayuttil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtsubwsnrp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtatjxsenp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtfiwbnnqx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtgfrgfgrj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtiuthzesz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtnoonwuai.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtfwptewpm.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtsulnojxb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtdzynawpy.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtjuexevgn.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtktlsvuzd.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfjdrycm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtkiwsopob.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtbdmokmqr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtqsiqyznt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtdqvojujr.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtyrdnojld.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtkloewmyd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtpygrboqu.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtqrwblohl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtcmnydbaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtrbpmymcz.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtrgvgaccb.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtbdpaelnk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtzbglhxbd.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtjcmtodem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtskeyiusc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtgbkyziox.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpayctpi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtbbcbzyxc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtfxtqjgvi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtwabvfdrj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqthqfiv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtwcvwjzzs.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtfervbean.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtcwueqety.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtszokhixq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gteujcvjji.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtvhwecqgh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtkxuyrsof.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtmhfasayv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtlfdhehgf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtzvsjuciq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtloyxfuiv.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngeizzbe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkuqjdsaz.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtfefavnfu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtbvxwpfdx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtwktjgvak.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtdvixkayr.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtohdquamn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtzskuhndc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtqxstzxsd.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gthdjbafxe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtadmfjhey.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtydgfqtpm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtzelbroza.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtaelolvam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtzjptgsnp.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtugfxfmns.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtnutpbkec.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxmopkbry.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtsunvoywj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtzrfwirrg.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtjggbapof.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwrspazw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtgpcnptut.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtmqnksvss.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtglumjwqm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtunxpbwpu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtdhrxblqa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtewzjnnoq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtxekgtfcj.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtpyjtnxvv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtphlzhnpw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtdujyjgag.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtuwgromsr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtxpjtnsep.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtcxvxvbbv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtvhlvwklr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtzuriiorb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtvvbiqcdr.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtibgxhvol.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtlkmzgreh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtfchomppm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtrjcicwnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtiysnbqna.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtqtxwyeqi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwktamojr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtccswihvn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gthmwkywdx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtsozgcygy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtsinwqdux.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbdkwuco.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtndcospri.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtnmmwhmnc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtmemmhsst.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtimczenyl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtcgiwwrul.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtalyesyod.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtblsqplmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtnqoiwsbq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtsyshtykp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtgstxqoll.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtaapyomgc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtifobbrin.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtnpuagqub.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtfgsgstuv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflljynit.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtgtbgfcmi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtjtgauavs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtbgirfxnz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtwjnhmbqq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtzrislorh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtviimvdhw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtoyktaohr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtrkoaybho.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtntdacnxh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsjsgpccw.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtmlzaywla.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrpiomgtf.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtdthtznut.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtswhdfvxm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtkmxrwpxb.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtxmnuuqpl.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtxuacabqe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtmrgwzjjd.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtjpgfzsyv.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtglubidcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtmunzdcbj.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtijdjirqg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtunrxcbps.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtvxnkqegd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtdrxsqodu.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtgwcocsvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtqmmumdlp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtibdsmqtv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtwoprtbtu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtkqazagsv.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtwlhlqkms.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gtpzzcqszw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtpwmvdiqx.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtzqwhhtms.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtlehfjwfx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtjctefrnt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpospznw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefgqurro.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtaktokult.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtwzbmgrye.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtqchgmpee.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtphxvyaes.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gteqtnfgfi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtscjduspw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtuigdmqsq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtkvriiijl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtwapzvpjk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtlqmhfbfd.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtmcfwlhlf.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtiusocxih.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtjzghudyi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtoyjelrfv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtxmjembdf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtpzfumtez.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtimykzlac.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnuogofy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqetpxioc.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtwahzujyo.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtutxmqtkr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gttgeiepoe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtyoardizk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtdluwhias.html


<!-- 参考信息 -->