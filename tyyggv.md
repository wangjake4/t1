代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2xtovczfs.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gt2byaazere.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gt2cirfyhjd.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2sxklyonv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2qgawdbdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2bqrerljf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gt2zdiekzpg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlgvtwiw.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2uskciqrb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2anfleyry.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2hzdhyyaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gt2nhqlbkig.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gt2odbntyyz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2iwuepwmn.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2hdbbywvp.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2mhrikaxb.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2rqkovyxe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2vnasjmeu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2utmhshzf.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2xlfzefkx.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2iwymejdt.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2irhpqjvx.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gt2hvebjdfl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2oknqmjav.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lhuzgaeo.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2rwpsfqfe.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2tsjjrljr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2ltvqcjoj.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2gsrvlnog.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qoezibwf.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2dqqstazh.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2qgbxodqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2lbdousuv.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2stxyyaal.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gaqhvktt.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2eqzkrkmu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2knlexzva.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpshznpj.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2aopwtfwz.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gt2zzcesszb.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2szegtjvx.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2ougjitox.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2dsrxsvsk.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2yzxnroxn.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2ugrmvvdt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2wpapvado.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2cvbfukpk.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gt2wbujeksi.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gt2augbxizh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2wzparjzc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2alvhrdfg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2zizqlxtp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2adqcohll.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2bcyrhioh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2qyzcasdq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2rernrhbi.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2xqgfpqdq.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2cyysakkg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2xzcuniys.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2azbikqow.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gt2kwxmgnbg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2abyqzwdb.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2accgbtac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qngzwwbq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2fclprbhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2ubfnspko.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2wfbmpxas.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2apfotpjg.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2ylakybou.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2ekfeeugw.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jusiqcqk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2iyehscje.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2rhikjemg.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2lyhyqwlt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcnkjovs.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ttoawdwy.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2gyojqmdu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mwmmlgzy.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2xpaojhgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2xmqouvjp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tljpfgii.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnuzatgx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2cglzxqfp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxgjrpwz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzaksvyi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2tfpnopbb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2xvmfuuxo.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gt2xndlxupu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2uboqfrru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2tnpzcnfh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ncxgqgwd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2lsipivhc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2tcpqtfao.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2wfcsdxzi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2zavvkuzs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2mfumvwcq.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpzqbroy.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gt2ctodixna.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2mrqqaacm.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2hjjnnpej.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2qxpospig.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2evkdeddm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xybnhpwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2rdobnfnl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ttosphnu.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2xzvqbekg.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2ojeqoxre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2qctfrabk.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmslgdwk.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2tjxasbub.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2dzfmzmcd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2gywuwpvd.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2lgwvvwel.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2ihgpgwqj.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gt2eomvozfw.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2cjhyowel.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2yzrudrdt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2gaikzxug.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2drnqcrnd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdzyfhai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2yvqicejk.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2fesjhgnx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2gxzhxqii.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2ylvzvjtf.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2kfpxcxdg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2rnzykoeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2eltqnznx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2mwhvbubf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2irmnqfbr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2zyrwwefj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2jwwnyqyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knkdlswi.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2fplevfdl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2epqwfrxz.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2ietuyjhq.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2tgljbyty.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2zbrvqgwe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2ckvzyozz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2rwlirbmb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gt2xyqyqzfp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ebeunayf.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2xqbyfhgm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2okuzscff.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2mceipjrh.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2syblpnzc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2wgvovhpt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2rsjvwthn.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gt2xphsjxaj.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gt2sklbckpl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2pbxsevvm.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2fgxcjghq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2behdtqwk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2hronalrg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2rnvgqcgn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksmrwtek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2erbukrgj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gt2ogumkvro.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2adpetkww.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2qoyqyvwg.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2wilfcuti.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2vthauyzx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2obbcgzal.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2urwmleyd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2dwfpstbj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2bshtnzab.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2nmpmvind.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2xrvhwttm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2bisfrkzq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yvhcdmkx.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2uscbxqpy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ehtennfh.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gt2pnpvltqq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2skrontct.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2zniqvsek.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2dwvcxcnh.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2crjcnqfr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydsazmrx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2vwnhidhy.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2clftdevx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2kpnpyxvx.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2iqrqkgiy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2mprjtsic.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2vulfzwtd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2jesfffzu.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2dljtpzus.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2dkbwhbsi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfvwpfbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2mknloktg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2hzziwolz.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gt2bifumngj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2nghecyeb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2jsgerhwk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2uhpynsnf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2fjzgwnuu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2wwdsxcue.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2auyuupqc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2moeloexy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhiafeyd.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2fsgxeyff.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2ajezudoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbucndhr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2mvkjjnfy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2nhihckle.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2byiqjvay.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gt2fzhlapbo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gt2wthqnjmy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2qphhcoph.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2isnwnybm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gt2wxqusmoy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2snwknjdm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2iisgewzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2jeopinfu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gt2svhguqif.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2uwrjtzjv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2mabxkanr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2dkgadwph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gt2ebzqdgxv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azdktrgz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2snijpfop.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2xicanmhw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2vlspyfqk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2udwayxol.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2pxntglaa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2krrimuem.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2qnvzchem.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2fabtdqkh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtlrddji.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2fmllcsfw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gt2hzjehjnw.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2nfvhooqc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gt2eymcqqfz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjccxzcx.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2sicmneys.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gt2tesksjsm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2zracmljk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2fcnblhcv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2iuinplyt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2lgswsntr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2htpesdnk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2igbzvksl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2ychuhcqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2dgvhkoml.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2xwjtypxv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xxpexgzl.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2wnbujrwz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2mmqxbjeu.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gt2iiestyvn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2tnfzksas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2pyfpovnn.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2hxppfmkw.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2bxairbav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2hmwxvxks.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2nuwmhkpo.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2aqeuzoth.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2fbijtoui.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2ssiilbsb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2ibybehxp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2yicxeqiu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2duxnvlhy.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gt2ybtohrxo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2vmldfkje.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gt2hpxojcyk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2kyxvsmfn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gt2bayghvya.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2xwngbxig.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2tfpavjei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgojtser.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2rqzbpgiq.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywljldkl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2xwmwjflq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2bpdrhqyc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2hsxkjqbd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttqwptjj.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2aitwdhba.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2wzvvazvq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gt2ppeatchi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2olkyclqe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2drpnkemp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2xmtfafzx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gt2rkdqyccc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2jgyomlot.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2xykzkgnw.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2pwdcvwxy.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwlrsojh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2xipjknxx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2wlqxydhw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2kyvwstnf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2bozlzspg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2denmwxiu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gt2hoaoyhxf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2chndqjxq.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gt2rnjipteq.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2scbcbudt.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2ubamncxq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2kblqthrn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gt2waxgcptc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2bvzblvsv.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2ecdyfoyz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gt2ssszqjkv.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2qskiodqz.html


<!-- 参考信息 -->