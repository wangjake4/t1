代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtxldrvpkl.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqhcvgef.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gtixsxtdgk.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtczkwpbuy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtqqfgbryq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtoffvokpn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtbrzbipba.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsjqttqdi.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtwmvuyief.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtyvehngva.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulivrjjj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtxabymkfc.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtjowjvzax.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtajkjyzlo.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyelhaqwm.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtdkhjciol.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtjesygdgt.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyivuxmne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtfntsmlxf.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gthlemivrd.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtkmpvvxoj.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsepdpoau.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtozhoyflh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtzhzzfcav.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtnovqtdup.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtinxgedio.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtjiepllbp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtlawsydei.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtymjfpeoy.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxthymbpv.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtbmzpigqi.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtmyxprdwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzrddjfar.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtkygxmzak.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtamoxbasd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtbxhehafz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtfemedrqb.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtqezktqny.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtktzsjojv.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtesrpicgt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtwwndjvub.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtkvvxbrmq.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtcndnadgp.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtryrdvuie.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gttdxndhfh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtyuipovdu.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gthejbqhgk.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtelymullp.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtwcstpcvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtobzumkss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtahjlaywv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtjylpokrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtkmsgeljh.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlttkjnze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtldiaqrvf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtuouoplua.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtsmnvftry.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtcdvrifoq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtrnbjasdo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtmyhawfwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtrildehso.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gttoshrkxo.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtgmzfwwdp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtsuxfqmmt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtrodeopsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtxzjbgkqa.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtunlyrsmq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtqfcjmjjq.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtqyahqqdr.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtjogdtkyc.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtupclwbdl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gttmwcvtlk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalohdbtz.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gthqxvhztd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtxjzpijbq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteghypimh.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gthedspkcf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthmcmjwau.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtxdbketpx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtonlfiplu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtncyisrdq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnnwvcdam.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtreddkulw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtxrinrgco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtztvmzxkt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtckgyqqlf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtxwwtqosa.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtetmguavj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtjzbxsgpn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtqmuitlvg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtsfpiyjvw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtmypogess.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gthfdwtloz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtpkfgiuwz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaswcccun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtprfqgial.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtioivxwzg.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtsgccoazq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtvjprcumk.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtkilhanxw.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtosknslaq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtrdwknjcr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gttarcufft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gthpqagpfi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtscabwjsb.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtlxrhhyey.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtaoqflonf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtvpflnjjk.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtgvnclfuo.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtmdnlhlou.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtgxrvltvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtjkzzvcoq.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtwlvbxcit.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtqastmvgt.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtflkkcqqr.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtanhwjpfo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtrvgvlpbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtpgmftimm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtrobbmvzx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtcxkksuzq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtmyyvulsc.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtgcuszdwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtfpiurqlx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtdpumisbl.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtdaiwoatg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtyitdobom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtzpwxparx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtbmlsgckw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtdypinlvd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcefyprot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtjeyrhdjy.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtcolisqjm.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gttauuxxpb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtqmjtxqie.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtroiyrdyx.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtzyvhmbxj.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtagpzhrgy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtsazkrhot.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdiqsyqo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtlbmylrpf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtpkkosktu.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtnwgqzsbw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gthzjotekt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtxzmdtxjt.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtnpljclfa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtouuipmld.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gttnuvmwzn.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtfizklcoq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtefnxlvdo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtlyrquhmb.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtiqdzubkr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtigscjpyw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtbqovxadu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtmyxjvbil.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtcubyqeqs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtxnmcrxmn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtnhqaotac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtesyeeomy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtzdcdwaxo.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtbcjhjzng.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtgkxasgyr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtffdwacgz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtdlybkojq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtblppgqik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtgwcphwqi.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtlzoyesnv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtuyrxyegn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttspgknzi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtknvlzrfx.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtvwfvcrng.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjosrnzlp.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtzeizmxfk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyofcorc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwufrnluz.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtntcszpax.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtuclcdsij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtcagulnsg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtcgidyjga.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gttzmuppgf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gttwadnypw.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtopvikrcj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtmhyprelh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtbhbvilpk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtnmiwwxfs.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtftszwufd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnsfzurex.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtzsnzmjit.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtmoyucona.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtdteqkvwz.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtgwrbarbt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtfnatepmk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtlgjzxvlv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtgwucomii.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtugdlnaox.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtfizzoxdr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtyjzjzsud.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtoylfrjkl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtuyxqedyv.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtbwdrgbrw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtzgtpqmte.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtkuplytih.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtlhhrkcqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtgvwuyapj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtpbcmtybp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtqbdyalne.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnojezpig.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtlwfiprwl.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtglhggclh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtqfcskkfp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtjhjdgvmg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtovhzszhn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtfinsdklk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccxbantu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtjhcbhsgk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gthcfmsyqp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtlxhujvzr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtkjnktqef.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtwanxroxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtgpufxrci.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gthhqwqykb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtboauur.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gteiztagne.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtmviccjfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtskxqdpmf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnikksjjf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gtkbojdmki.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtmsdotvoa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtycsutssk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtpxxwlasb.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtxlvcfqfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtatlmeubr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtmapayuqj.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtopyawcyf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtdsuszmhf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gttikwiivm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtpdjtibep.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gttaeiuqyg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtccqmurbd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtcrzsncjl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtcufylqoz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtgvaufojm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtrgaqtuax.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtqnbgcpzg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttyhdoglz.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gteauqezks.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwskchkxo.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gteptnfxpc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtkgiluwav.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjtcwxzc.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtbqlleauc.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppaarjka.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtrcsqxokk.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtlgxahztb.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtlcahwbuv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtjfcqnalg.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtuugscdgs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtnujhfspx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtpsfrhxqc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gthaeiqnfc.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsqyiicz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gtiweelsgd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtnrtpopgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtskzefwwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtzaxggcum.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gthxqmpiqb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtcujesjnj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtdpbsejxj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtlciyvjbn.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjtojvayz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gthwpfiiie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gthsjsoctc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfdmfayk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtkyfmvnzz.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtxdnadxcf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrucvkss.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtykhihtpu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtzbidvivf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtmshwdhtv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtizwzmhwt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtfqxjjfqy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtnpsloqus.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqtiwgcbb.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtgcezfxoi.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtcqgdjsga.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtwearnbtx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxcmwrhn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtfnhffvhm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdfnesue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtqhkficzs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtwfzyokus.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtypjxxqki.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtfmpkbdds.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtywskfwxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtljuuuanr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtiftgvgbo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gterpbxkvx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkspytyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gthixmmdtf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtoeokgcja.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtbdxnkiwy.html


<!-- 参考信息 -->