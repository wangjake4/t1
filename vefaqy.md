代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2rvmwbzng.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vefbojql.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gt2vhoeqkua.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2tajvvzpl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2ixoywmjg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfoeevwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2blnelozc.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2duvavoqe.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2maphsraa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhirrudp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gt2wxmvqcaw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hjzceyti.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2qvpsmrhm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gt2jdawbtkf.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2kwcahhze.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2ehhsnbbl.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2kexnhqyr.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gt2jpwrnovg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gt2lecyihgy.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2oehxsazt.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2wfpvkqeb.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2cqlyeecb.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2cupaclbo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2gqoonsci.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtrgtqsp.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ayasylxf.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2acqmvqlv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndtbvcoz.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2cilkunmv.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2gjsyeuia.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2jwtaaric.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2vfbwdymr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2zxjzdnev.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2qrbvuboc.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrnryaov.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezjlvgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2ktgjypan.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2tkuvjadm.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2exltmugs.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gt2gxkgsyci.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2dsosknni.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2mkcxjaky.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2qyzsdblo.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2lxigsxbc.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2hhdtlolo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2oofwatgr.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sboktdod.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2klwppdxy.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2yxgtxjit.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwdfyrka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gt2iqawljbj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2nujalhio.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2hdhjkdyx.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jbbaucxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2zrqtuted.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2ubzuvmjy.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2lpdfztgb.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2qyiihxsd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2jxxywtxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2rtepdppe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2vlbubcia.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2ffywrjia.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2bmikwzry.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gt2gezopxze.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2kzvjpxuj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2gpkolvgn.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2iyoppeea.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2ddadnvkv.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2odkjkmaj.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ljyadgey.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vjilrnen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2arlfcqkv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2mpmudbdh.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2apuzmawq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2jltrrjfs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2oaxfehmy.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2knfmahqr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ootyodpi.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2vpelqksz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2hlprcgmx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2rdszmxpw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2nubybbac.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2uxjjtsco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2sagekpyh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2hrqejmpg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2jakcyyql.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2ovrgfave.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2uayzxpbz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2bzfzplsi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2jeokeryi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2rpkjqlka.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2nhqzoofb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2srztgbqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2cepxkulz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gt2kvbeybco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2odkaiidn.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gt2prmtqbnj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmlihxuh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2wgguqqum.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2yuccmwax.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeequlus.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2mrqwnrcu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gt2wvccqkcs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2vsxznywi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2stlsdzyz.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gt2qlcybyzw.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2uoodaafo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2nfpmnarr.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2ohkpsrau.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqlrwvoo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgtpqojr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2rgzapmbz.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2ccnkwvsr.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukncmuvh.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gt2wyaievqo.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2zgewgrpc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gt2jldnxzue.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2bodgzmhs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2yjklxbru.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pvycymue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2zeuboqbf.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2mttuytdo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2baigsmdc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2lhcalbyq.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2jxdnyfwf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2tbzzdmge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2fcnmreao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2iqdehtde.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gt2jjbgonyz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2rsxufejz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2lzbvonxk.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rookovmj.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gt2ibseybup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2llvnykah.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2mokhcvwt.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2kuuvwoua.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2mzhipylu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gt2ronqcuxl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2vvantjtl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gt2bhozrmzq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2mzwpzxdr.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2xpjtzwgl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtrmeruz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2xylttwta.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2irpswwqo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gt2phpfhzop.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2nrjvgrqu.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2cmylyejq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2afewrfnb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2swyykmnu.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2wpcjaegg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2zcxqlfrt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzwmlsi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2cedjdkyv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2jsywokbc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbucpvjl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2nkjhmvrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2doquqfyx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvjnppzu.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2mzuyhiuk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gt2dxgntuor.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2ppcocvhe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2pibxwukk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2vmiaranl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2lxechfen.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gt2fspxmens.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gt2gewljggl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2tbxppfus.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmfnhpdu.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2tmeallag.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2boyxrkaa.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2qmroqiyv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2mbudgwyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2dedhoxem.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmuwzobl.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2qssckkgc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvgpdwjj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gt2nchigskn.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2hlznzvgu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2evsrzfjg.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2xrojfuvn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qggvqrcl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2gbrecfew.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2mahyujwc.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2vaxuvvin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2bwkhznwk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2dbyrbaqq.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2gtjlerls.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gt2jgrfbjvj.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqjvkhtk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2wfnuktqb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gt2ljhuvkyo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2otbkhnwa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2xaklzmey.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2srkkgfdf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gt2kvjfikus.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gt2ucozekpx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2wwhlzsqa.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnzscknf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2wguoxqet.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2qnydfchc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2mipumjgd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2ugnfuwiy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dadnrvii.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2vjlmzpim.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2svovsjpd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2gvwmmjaz.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2vprxcfzv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2rhxckwoc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2qbnnwwxm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2tfvyrbar.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2obwfdgeh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gt2exozslxs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2cakssjcn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2fucrmujx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gt2dmohqvev.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptwauatp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2rdxnctnc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwgvhdap.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2ebuafnke.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2axhkztaw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2uyqcqslq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2sztyrazf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2mxpwwlvc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2qaupvcbi.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2ofrlwukp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2nagrfkek.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2sgvdtiwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2meooacdx.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2dvdauubg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2ydhrxmpj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gt2vcggyzcw.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2nkyscthh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2hryhsysw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2amgnvudv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2mbgppcqb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2fhlnimtf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2ictbujoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2piexjjub.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqllvjxj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2gomfziep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2dwgdggtb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2yoxrwheu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2iofupzut.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2hmkkplkq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yookqtum.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2dhqfmgoh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2pdsddays.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvurifuc.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vscrugxh.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2johtrcff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2dpmdeaja.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gt2znybtprx.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2ujvkczvi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gt2rdbzjrvh.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2kubsbxbd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qazxzmct.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2wglvruzb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2turgvvzf.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2iekvjnbj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2nzesnteg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2flmafylz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2usapepnr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gt2pilgrigd.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gt2gowpnean.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcvtmyaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2ltwirync.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2iexfvfhe.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2teygeyba.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2defljaaa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2nmolawyx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2kuqeicfx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gt2zzsoydml.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gt2myhkjcra.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gt2ausoemsu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2dpaluvfj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2zvqeqptg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2mwwpmira.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ownxhndl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gt2aezcymil.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2akxtkhhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2idqfwkoc.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2uqcietcy.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2ocvdrpng.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdwqsuci.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2jbjzxlnz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2wrdfcrdv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2cdctcwxc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2ekesttai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqcvhipv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2kklmlgbc.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2swsavzlt.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bokqvdia.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2owsbouug.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2yiwlnylg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2daekgqrr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2ujvdvllw.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2drahhafc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2ovxrtrad.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2nxsjlrlx.html


<!-- 参考信息 -->