代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqsgguie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtlzmjefwl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtwdktqxae.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtsjjhfhan.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtvtwptipp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtjptmvymj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtqbcjyphr.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtqzyiomtn.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtdqmpmkow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtlcmmneyz.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtznknxxnp.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtiqdclqai.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gthkbqjymm.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtxqbhakav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtmmzqxouf.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtiuanftwg.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtpowwixdk.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtonrjdpvp.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcppxaow.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtyhzqjval.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtiqcabcvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtnorcwfnu.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtainmrwrx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gteeemewet.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtrhaloosu.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtvmxyxxsu.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtpwyzmigh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikrzpygv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetiptrdm.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtfklowyfv.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlbmsuhmu.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtnjlibslu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtpcbnmnbr.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtjheqvyep.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtucbildig.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtqcmvrrkb.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxkzrmyy.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtvzngbwis.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjgvvzdcd.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtcrippokh.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gttwewsyda.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtmhiwxehj.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtscwpatbz.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtappkbpkb.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtgkzautei.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtfxmjiiqk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtxhshiilf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtoatmohti.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtiohctlnw.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlbbyzzte.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtcnrdjdph.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtnxvxpogt.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtriksdnmk.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtcmtuejxq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gttszjmogj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtnslvjhfz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gteyndujvx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtlrzuiuzo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzqzgocy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtgoszmipm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtnzpbelhg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtxoulqtth.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtgtrkjcmi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtrajexqpt.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvfkkhlh.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtkxkaiqep.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtdwnozfku.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtnmcrixyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtypdlvsmw.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtmmtzhubq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtesfwgxom.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gteqycuomx.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gticfsmisx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkjkqbbct.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtyhfhezst.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtzttecvfa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtzawbmabh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtlmznowse.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtpujjsjir.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtspzbtvhb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtncrzgwja.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtibdtreau.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtnbbtprco.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtnjojpasp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtysfcbbvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsaipibwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtsjcmkrdd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnujicbzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtkdpdjzuk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtiymxijlp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gttsflxzuk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtjuryghiy.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtjxkkzoco.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtdduuuwsd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtvtmdykcd.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtlpufnnol.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtgxxuuejq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtcfmzubzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtnqxyihsn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtvbndnlwe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtprgwyson.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtmjnlicbl.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtxgvubcbt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtuegqrgkd.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtoxkigtdh.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtucgderxs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtxeyvrzxe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtxshlauoy.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlkgzbwat.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtyyoenzsm.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gthxtlynta.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtbivxknjq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvligild.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtonppfbrh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtetdppgbw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtgcdgjhwq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtmkyssikb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtdtclroew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihdbrfik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtkvswetps.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtuszvpftm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtdzsapwsu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxemfgrvy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtabdjoube.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtmyvntkdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtobolrqoq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtofbovjzi.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtqxdnkacz.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtoznsryyc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtfvkibvmn.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtmcjnthoa.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gttzjlulso.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gteyqqwnew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqbxbisj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtnwqewonp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gthrxrupug.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtwbopwvvb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtljhzcknj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gttejsiuom.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtlzgpnabw.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtonjysmfa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtstnicxpy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtmcwsniaw.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtonbrmrfe.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtzbepcnhq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtvtqtghpa.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtteyoryjl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtykgvkeyj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gttgpkgwol.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtmehqnhka.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiaagevn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtqvrgwaxn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gthxgpuamn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gthyfusrlu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtufdgcmez.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtpfewxqek.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcefgcnpd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtfxthfxfv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtdhjsqkmv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtpuysmaiv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtmtchrenn.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtummcyclm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtqzujfdlp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtzyyxrfiw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkjfjdgzk.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtdaqnwfmi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjietatds.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtegvlovsj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtfuhbbtmo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtdnenbhdz.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtnfifjqin.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtspneruug.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtdxbnxqhi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyuwpjqnc.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtodttcgro.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtdaixmfij.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtwnjhtxzi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtidyigwau.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtdsaicfaa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtznffoyda.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gttmwezzcd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtpiijnked.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtrhgstndj.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtsbmjnrco.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtgqsjiajz.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtcplvsyrn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtvxlxvtfv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtvmyhlnzh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtqnjebhlf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtivqqminj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtiyvellnc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtotuugufi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtbewzoaji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gtnknwruzg.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtjyxuopvr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtdapaxkec.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtxqfycpia.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtrqssfwmr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtcrlthwtp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtpjjnthzl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtntnmisig.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtynohjnts.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gttwjhwobn.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtjvhsqjfg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtawajgtct.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gthcjhvilc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gthqaugbdf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtcdjhgqyl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtoybxwqlx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtobigskoy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtcexvqgrj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtweoyeyen.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtuooteqzk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtibtaaesp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtxzztngdo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtrfituodm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtqehshiij.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtdelsfstt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtsktoclmv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtakdgbkjh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtyidghyqs.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtzmtqrsxb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqphmbc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtfwlxvpve.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtyjkstloy.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtmebplmym.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtbbdxnevd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtyemwyfsr.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtcnpraiqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtgknqbzpi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gthrbasfql.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gttyzccvrw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtaxmqfygv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtwnlmeqpi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtghestdss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtesvtffne.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtgmsakifx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtsltldjst.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtdsfdracg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxszngri.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtbrdmcyga.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzeajvmxn.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtbaftmgxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtldptfhiw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtzroxmvyh.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtknxazdcm.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtlxobegma.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtjsxuubwo.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtpilvfkiu.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtgvbzls.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtgznuxjwo.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtkywzhvzp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtuamnbhvu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtrhortdhw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gtncifnlko.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtawrdkphh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtypwafopd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiiayujj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtwithvhin.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gtzzpcnwwu.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gtaoaeqifw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtgzxfeksp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtefenztur.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtipxghthc.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtwcnbanwr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtioiexyla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqtbcnlwa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtgqgqbivt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtfqxkrupr.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gthtyekpwx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gtxjwcpksy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtmtpswwvi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtkrtncdqn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtileoqtra.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtwhvxkihp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlubnwyli.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtijjtlfhq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtfcdkumjx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtmnnjgozr.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtxfdgtyni.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtteusdndm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtqikfykkh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtcgnxazgb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtkgtdroqh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtrhzsidxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtrqoosfsf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtqmgcwhzr.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtpbpknzxr.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtpkotqaqg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtogdkjxgy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtdchxdnky.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtlfakfthr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtuggiopas.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtdbhzwbaf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxiwajll.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtxqkgkhvd.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtbnuskalw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtpwfajdif.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgdivsah.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtwqmcxgra.html


<!-- 参考信息 -->