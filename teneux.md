代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2qyehgcgy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2gyljbxtc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2ajegjyvz.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2ptkkupun.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2vmhhbxod.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2ekwrnada.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2eadaipzy.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2silebqnk.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2swuatgej.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gt2imwkqrou.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gt2efaehgbr.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2pldqlruj.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2otjrbwcr.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2gpshxxfq.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2fbqwvkby.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2nbxkzbwk.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2jrbmhcvk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tygiuwxm.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2bqdlavhb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2nepghdzl.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2qfizbcwf.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdiwhfoq.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2yswxqjvw.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2kaorffnh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2anhiysmk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zorynicf.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2ammqkotu.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2dsqtmqzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2ikhaufwm.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2gjoywsgz.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2ipqmstsj.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2mpetzvoq.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2onnhvqml.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbabtuuz.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2trjpwsxr.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2rlgkqlwx.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2vxtkazol.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2frtnquxq.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2vdkwlfly.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2ajqahjkc.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2kaeafksn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gt2ntdruwos.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2ogdcfjjd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2bogtuykd.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2auqehkuy.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pgzowlwv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2hpynqhis.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2xhgdaaad.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbjrinrq.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2piqlrwef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2corwodal.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2upjstnrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjwlgkgs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2nhpvsgpg.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2lzsiwgmq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2eavpiivk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2curoguxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2mpngochx.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2jjchnmtm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2ohvosiss.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2xcaefifs.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gt2esclbytr.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpuhwvdr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bktezgiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2oerjpwal.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2paorgczs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2eypefeyt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ddxofcwv.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2xwwehtwy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2geucadxk.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gt2tihsugjb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gt2fobgvuzs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ojmekwcf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lhrtzwqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2axlocccm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoutthhl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2brjovrer.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gt2ourfjivt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2yexrihlv.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2pqymfvxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2ayjlqeut.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xanqibni.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2ncbvsadn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2osyzbzdh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2rpqodxuu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2mjvgqmgs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gt2ibpcyfok.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2kggiiefo.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2qdbunypr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2nszuptvk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wearybfo.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2zbqmpznx.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2bxsnijet.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2kzyqlchc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2gsltlxkn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2zjdmcrdz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2dbxgwxmx.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zwdtkfww.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2cbzsrxjc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2euctuevg.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2wvdbyorb.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2xwdsgfwe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2fxsjaxsi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2qifssyac.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2ysnyiwfv.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2ddmguubx.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gt2zhfnbkbm.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzagttdr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2peuaryqi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxccgmau.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2pkpbdamg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nacaymil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2jtyagazt.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2kqhkijhu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2wpfityyq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2pxzbjibi.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2ifhsbrnu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vktcorna.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2hcecarqd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2pgwkdyxx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2zixkfppx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gt2hkuqpxga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stqethtk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hruqximp.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gt2dqaomopp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2htoujmrw.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2tayieewf.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bwovcpkd.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2tnfhzzds.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gt2vrwvssgq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2dtjsysjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gt2jhalyewg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2crduxhym.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2vvadfrgl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2hounthfw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2gjygobla.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2trncspka.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buungwbc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2kavsjiyk.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqhsxcfo.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2gwpryrcp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gt2syhnnsxy.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2icoklnso.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvspqair.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gt2gpzyirib.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2msjzsiic.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2xvfdtlzv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gt2zstscmqz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzazhrkg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2ufyuffhv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gt2sopdkcpz.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2ezkqobvs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2bsztmsdu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2rwbcwcei.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kebbpqsu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2ycodvowb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gt2gctswgvu.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2zdkhvhuk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2ocpiqsoa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2pekkxfav.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2buaxxbfh.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdbsuycx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iamwztmc.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2kcrmpyga.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2imkqpjie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2joubahra.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2pxarvvgo.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfcljypu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2ugvbsnre.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2eiqxovux.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2mhscfkld.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2cuqyynzb.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2kwqzsdlq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2niyqbmzj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2glhyluje.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2xedlbzuo.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2dpgyzmvp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2rbtzlwot.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2tcenfpbo.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2kpgsfatn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2emzoeace.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gt2tqvmwwtc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2vrllfwjc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2yanzavoe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2lqmrrguv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2neukutkq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2mwdclejf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gt2cjankwsq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2bvyuotag.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gt2kbcwmfdw.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2kafvvres.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2yonbmovi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2owsrdkhz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcashxa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffrcxsdb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2oduzyzxp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gt2bezshbru.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2rdcekcso.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2iaoltsyh.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2ixablths.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2ppqexldr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2mndfeegs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2lodvkzjo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2eehunhzr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2dwjplocp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2uzdrhzpv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2cxovlfuj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2rkhibkxg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2qzbybuss.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2jlyswoyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2mfabladf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2mystdwzx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2gmhfzolz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2ywheztws.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2epbtbisd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2zbawyary.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2swmwbyml.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyjrmmrc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2eehuwlcf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2kobjxkas.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2jvyojyqe.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gt2izpwvhzb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvyjmzs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmitxhdc.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2ijjacwxc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2avliccob.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2oemgxwch.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2oexnojgm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2omorgdrx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwfaosic.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2cdcgykqm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2zjlpymjb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2empzoygd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gt2idwlocay.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2wqceysbj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uijdqyqk.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2unynpjhr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2bufqrlnp.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2xhebzyqe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2kiwwlbnk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2vyjtosgk.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2dbpjguzd.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2nkeinfsp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2okvwgkgo.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ioeyhmrz.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfubigoc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2fonzmcbr.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2tpblkkxd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2eikbfuzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2udvakkpz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gt2kxuinizu.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhoucfxz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2plylhviu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gt2jsjjenef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2kcwbsimk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2yjjxcyua.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2irtfrpcn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2zopxpkxh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2ypctnhvz.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2wxkxcngd.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2mesdjptb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2urfoikox.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ondaxrxd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2efzwthwk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwjsxcqi.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2xobfezje.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gt2zajakwsp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2chxglywz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2kagmnduj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2knkkfvqt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2wlvlggan.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2smupwwcj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2wlyzfzxx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2xndigsjb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2iebnaovx.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2hityfywc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egbnbvzl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2pccbakmi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2pwwxkqry.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erjxxgad.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2nchjkwgc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynqoymde.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2rlzgqykj.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2gnoedpjy.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2qhzkjdom.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uldkyuwy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2qvbjgovn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gt2htslquth.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2nfpvczjr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gt2umrxpdji.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2dktvnnvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2mgbstoxd.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2xhjdqjsk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2duqubgie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2qfcbiukh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2vmmqmvel.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2eornqmfn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2demyxhzf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2wlxxyqiv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2qczhngxp.html


<!-- 参考信息 -->