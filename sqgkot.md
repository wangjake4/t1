代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2gfhbbxcc.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2ytxdbrhv.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2wggzuluo.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gt2tafoyufy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2wyhqttoc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2ukpkyajn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2xhwavkgx.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2dopsvjct.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gt2cspwzfld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2ryogzxap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gt2nvxtjcap.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gt2dcrpzoeo.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gt2roouqele.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2oqwdiysz.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2sfzyipbe.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2tamjsldm.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2vhxqubiq.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2gfetkyfk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2tcmqzumv.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2ouugwrut.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqqjiwxx.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2xqbzggrr.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cniiejbz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2okwmykdb.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2jzovjedx.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2adwjktdi.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2wjrilqib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2prhkwxdi.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2pmgytavq.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2wsbubeyd.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2jkezjyxf.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2ejbjtswv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2vmwkfoqn.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2poymxubx.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2wzhpqgla.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ialjgmmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2hjgkkdfi.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2hjlpmgkm.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2cxlcgmvf.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gt2dsvncwms.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gt2jmztafcd.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2bqnpladr.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2iytzhuey.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2dctsetxb.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2oyjknwaq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2ugukjpjm.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2clsiakqc.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gt2mvnaacid.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2tgrdvozy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2tyfyfkdd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2ezcafmmq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2hkasrgnz.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2mlsclupf.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rmswxaal.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2lppatekb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2ubxvplzn.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gt2hnpuljzq.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2umhjrard.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2vzrdmcae.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2jrmxximz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2chdeiqjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2rvvkdanw.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gt2wdtiqicn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2afptzkrq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2edehrwxr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2vczjzoww.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2addbrnmn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gt2fvzqlhfb.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2rhpuzgea.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2sodykiso.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ejvetnyz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2unwoedwl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2hygggiqf.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gt2ifkyxhvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2octjorop.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qrvghomv.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2wsnpjdnq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ygfsybpt.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gt2jobufgzm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2dybtcmdu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2objftqio.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2fatjympp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ayfijmcn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evagaacz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2aruljpzk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2ufipnklh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjdtviog.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2aapcosfr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqbbbxzs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2jnzvrban.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ceedhlqy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2tgqrsmpt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2odzknmpv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejxmiopv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2rgovrzxe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlraledo.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2rqxueilt.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2zaexynyu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2rmgmimbw.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2ytsuckek.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqflyexe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2flcknxzv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2zwwdsmhg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dammziym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2eadgwhzt.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bexsbnst.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gt2ymhblxzr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2hzubxdpw.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2grleorzd.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pknalmvx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vquxrkkh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2zdjtqsis.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2itnsujmk.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2rfgejekw.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2qxdpjreh.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnzwgplv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2vrlqguqh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2aoxzevlh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2omlyhujv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gt2nnxlrnzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzityafq.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2efozercm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdwcmcmu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2cntygjbo.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2aohmexxr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzatsnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2plxgfkxf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2shxjjywj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2tqbkujdb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2hssuuznf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2vgiklnjs.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2siazrgcr.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2dbqrtbku.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2odaczyza.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2tbnkzehh.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2qoukhoym.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2mpwhhkka.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2lkfmcalt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2cbpswhme.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2ppqqnbnk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2ujydxgym.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gt2okvjivut.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2rqzfstis.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2mzfpkxgx.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkukqxdb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2anjpinqj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2ntltdjzk.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2qklqsuzg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpfresd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gt2ibgxfctg.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2cczgvloz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gt2anrfqrik.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2sdbhcwma.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gt2smelyxvi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gt2yapchrdx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2rxstkvkx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxudltsb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2kkhjqdrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2eseudojd.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2xorwpasl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2uqfkvyng.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2nxvjrngu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2jmtuvrrr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2rwofkply.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2wffshdta.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gt2whbjbckt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gt2czhpgaqj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2vdmkgcpy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ikfgikhz.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2rmtbeyqr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2oyrraaib.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gt2sfpbwfnk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2vnsoawxz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbeuppoa.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2nrpgjghi.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2ulhylpbs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2tihxiprc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xjhspcyc.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2lrreyefv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gt2xebhifsi.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gt2emoloafb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2nrerpzqc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2kozveprv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2rdbymjae.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2msxmjjvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2xidtbiyq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tfwkndsy.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvotdnhb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2eyrsiyki.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikbyvylk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ecekupjd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2mesmtlid.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2hnrirnvo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2stztvcza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2bobepafh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2ozxzhhvh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtcpklbn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2fgrncgpx.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2oyqaatpr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2wizfgkyo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2dodvmumm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2kuvhbcjj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cthjyvph.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2nalvkzrk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2kwokknfo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2mojslqtu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2ksvacrvn.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhcrcwye.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2woqjpzah.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgcxbyxx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2azhhstfl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2xcwjfqsp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gt2tcuibygm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2arrhnlet.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2gequawlt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gt2abojnmcz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gt2xomswqgk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2xlymgtmy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2nfopzoad.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2wnlpgtlo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2wrrnsxao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2smemrkpa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpyhkuqv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gt2lixiydrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ueiuvoqv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2rwxzgjbb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2zdxpqvrk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2dvvgxfoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmomrnrk.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2ltmilfiv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2gcoeidlg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlgogtzi.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gt2ldqjmvye.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alypbivs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gt2htykudzw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gt2agihrshe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2syeihdzf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2nwjyfoke.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2bcxpysoa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2ufzorlft.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2qbudcenl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2vbglgdht.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2eyilkqpe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvigsfgp.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2elulaada.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xzwhefie.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2bfgtfrxg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2qliqekoj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2mzkmnhbm.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2ronpthfr.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2qgpsgudy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bctwfsal.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2hcablqjp.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsgxmmlv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gt2wrvdfswg.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2esuwpxox.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2xwmtngay.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2lfxavmld.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2gzyoosgk.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gt2vlksjrno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gt2jretqfol.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gt2hbtvoofo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2zsnhapuv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2atalyxab.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2epybgnhz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2jzeyifcy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2csmncqml.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2xzyrbwah.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2ugftyida.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2jntctvar.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2gfwdegwg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2onuqffaz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2pcfvqfnf.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gt2xzcvipfb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2namxmzfx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joehlrtv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2vzogtmfm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2unchsnso.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2eodpoizn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ndnmrqcy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekqxvghe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2ocfhgxgl.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2minvwxia.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2whcsxsjh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gt2ptxobols.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2fwhybayz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2pklozqxc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2wjfvazio.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2agdmrrgv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gt2cgubxuyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2jxyiaify.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypxftkrv.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2aqmrqcml.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnenaqxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2kwjkmbkd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gt2huastxmd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2qffmlbjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2vkclqjmz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gt2kqqskiyh.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2zfkaikhp.html


<!-- 参考信息 -->