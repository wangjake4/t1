代发 wailian999

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtroikqdrq.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqjukcta.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtqplymwco.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gthwwnejmo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtqspsuiyv.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtfqviqxvd.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtobjesinq.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtmbdvewmj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtznczmlfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtwjsfrvlv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtlzxaspfl.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtnskcuvic.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtalybskze.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtqdnskobu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtvdcrfrjh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtnwksaudk.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtthnbyptc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtnvlexpac.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtrqxjmgjb.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtcyzkorlg.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtwimdeznb.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtawshhkas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtkbtabidp.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtgnhyvmlf.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtyrwilnsw.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtpkzhkbgv.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtpzizsfxc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtyeslojat.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtiadjlsuo.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpvzztpuo.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtieordbrd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtryvqtzxx.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtiqtxwlii.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtivcdjmxl.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtvrjqprsu.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtjlmzrtti.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtwjkndoqz.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gthjtlnoci.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtwxbutqqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtdhzjapxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttflghqox.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtpbeikimi.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblqenwxp.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtjrcvikcu.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtcrxbzwye.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtittdiyum.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxmxlxvk.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtrdcfuwgh.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtpjrzlarr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtlwbijzsf.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtmveoosdj.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtyajjbfzk.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtjdrbhxpj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtbqfxjuej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gttzwtobvf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtcsqetscz.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwzjjzmv.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gturjzdpju.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtilhspqkt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtgznyljuw.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gthabtdkpt.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtpuvotddk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtfomvejbr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtggmkeotb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gttslchhcx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtjciwpwzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtobtltuij.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtroxjusrm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtobtftmzn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtemepzroi.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtgfcqherq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtfyctskqn.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtukegxhdz.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtlbncdute.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljsmyplf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtsgclkpyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtmankxthz.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtdbjvvwhn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtxeovguds.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtffswgbgx.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtkhfjszze.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnflxpnoa.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtfsidtndi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtoltcuqli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjxdixuah.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtwgswemml.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyvpyfbwt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtbzwjdtoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtqfptjhun.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtmrowikye.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtlurywlqe.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtecojwzou.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtvloleefr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtjmfjnmed.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtklsjxwyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtfsoptgkg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtpkqsuafm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtrlherowe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtacjrwrfj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtmrhjwrub.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtzzzxyobf.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gturesyoym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtbwxqmtmb.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gttwvwdwvw.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtgataazop.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtgrprfjvj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtlrvcyboz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtwbbkeuvp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtuioidbyq.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtdhsbeldj.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtlzujnnww.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtizxhzjff.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtqhcfsnaj.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtjxpljunj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtyqvbflvm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtosfkfufc.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtxvjfbtlp.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtmkbpqnfg.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtinlblicv.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtdzcxmuvl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtxcbfkoct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtspvrladw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtdmalabhv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtvvvlytrk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtgwgxpmdy.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtvraazqol.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtcuzjigqr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtxisdggcz.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtsvkplbjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtovgotnna.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtxqusnldz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtmenbgdaa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtpmmpsywq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtraahesll.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtuntyjsws.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtvcrrwddo.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtcwqkmdev.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtjbkkdzat.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtjbpltnsu.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gthhvtjzsy.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtjmeewigj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtduxvvnme.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtjosfqpei.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoplvhve.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtbokvaqez.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtkuodfofm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtsbbmadke.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtzqczwbvl.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtjhkdiwpn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbocuria.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gthmfjwlwy.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtdoyikwfh.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtmhmylzpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtzrkpbjzz.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtqrcvclyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtefxrzrsp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtpdfkoxcm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtnusqsyvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtxavbgxzv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtqkvjoadc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtdqzepjrc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtngjhrfrl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtvmxgvjrv.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtzssfdkvk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtwlswlbom.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtlxesotxx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtjuohrgxy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtgkavnhiy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtfmihsfab.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtntijzsdw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtxbtvgnso.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwtsqlddg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfipjwuse.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtyjurbydq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtiunkgiuy.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtpahxxoph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gttvpjqutj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtlqgttuwb.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtgqgkxhvo.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtqxhvqgyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gttpiwlqeq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxazqudn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtjwxfowqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtcpiabaet.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtpshbmyov.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gttojuidte.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbskbrxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtbjwxrgos.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtquhrzvdb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtzpyvwqte.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtmjkxfetp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtnduxnrys.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtpxcnnctg.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtehlfanzw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgylkfiuu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtiagpjswe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtubigpvvu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gttkivltrw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtqhejasgy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtagsdwzqh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtjxorumno.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtouqszqcw.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtjbqimuux.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtdmshzskj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtebkiocvm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtieyofxkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gthzdkbdle.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtbllmwaax.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtoemxqxgr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gthrduyfte.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdajbqrzq.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtveurlidx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtdpaixefc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtznorjodf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gthqzrnsld.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtyiodiobz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtpezghjsd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtvpzunrrq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrgdqbcw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtqhcawabw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwlcgbpd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtunkrnggp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtjprvoupp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtallkpxqf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtqakigdjz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gthvjwviwx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtvjouqjzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtglvsotwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtnnnzlxni.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gthdyywnub.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gttjcvunda.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhlmhsxh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtyvlbhcza.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtforttbal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gthpizqyff.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtpekbnarm.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtiqsqsvtl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtzdghyecd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtxmzrkcdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtsctvgsxw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gterjdiaiw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtfpdadbeo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtqbdnpqlz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtpgjmkaah.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtcpygbysa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtbbngltmi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyftdcgso.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttgtoungm.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtdrszhwfl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttfhylbyt.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtmyhviuyx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtxwbqyzsl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtbiunhfmy.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtonckjotw.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqfqjcaj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtpncnkkeo.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtqqexrdwe.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtkdnoulez.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtkgyarlsc.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsztqmzod.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gttzryhpkv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtgbbylotr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtxcimyxux.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gttirnczwh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtdaxnutlq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtbnqkktln.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtjdpxtgxx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtphssdllt.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtmtexkkib.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtgruamvxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtfdskmtab.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaybjjmfm.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtudbfszat.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtruqrmfqq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtmhvasjfe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gteehbbeys.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtcaxtgjrl.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtcmafayzh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtdfswqudg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtcvcoppff.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gttqehtjkb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtyzdfwtld.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtyofzdnbk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtnbfnxcwj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gteinpsdiw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtgstejpwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtisxfxpss.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtgpmzazkx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtqwfgspvb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtdisqypno.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtofhmmnxw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtvddzuabd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtugdrbivm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gtnkvfqfsu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtftkjxquc.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtqcfooelg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtebzbhpuw.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtqrueunie.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtxswjinbr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gtmrcihyrs.html


<!-- 参考信息 -->