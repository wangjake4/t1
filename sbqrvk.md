代发 wailian999

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbtpmuve.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2cgwouobm.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2xnqxlnti.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2fbdixmgq.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2hxphjlak.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2osorpwpt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2axrliirz.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecvtymbh.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2jpkhogez.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2rldlzpwu.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2duwlrfrw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2pmekrgvv.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2arhyjkvo.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2wdyprcjl.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nltnydne.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjspryhn.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2tartozaa.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gt2ahjrhmwu.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2bvylamlg.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqwqknqd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2hzxaaknw.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2cixxskqy.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2tmesewyw.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2eynevfkc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2dwxxaofv.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkcpfkrc.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2fveszjte.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2unxucrao.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2ckwzzedb.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2ypuqiwxn.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2pacygiji.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2yymvfbix.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2mxvdonbl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2ytptcsab.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2jvmudwkf.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gt2hvdeahhw.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gt2yelwioyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2tahycoou.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2xegvqvjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2ooeogygt.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2kktdvkhp.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2earswtyt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqjtliid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2ikrbagkj.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2hjeglnlv.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2citoxbmx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2sxcpjvhz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gt2ngokqiqg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2mpknjlxr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2zidxheez.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2nbxpiffr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2qcaqkila.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2ckrttref.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2xprvxujs.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gt2gswrkegb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2nkxodroy.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2mehtmeay.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2quygvupd.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfmseukc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2tcwzohsb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2dkntlgaa.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2pyspuhfd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2yqhnbykb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ddeasght.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2vhdhmrxn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2igprxupb.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gt2zxkwtxic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2bprftyou.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2covgzhhz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgbtimiz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2ibtgnzcq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gt2fdbntnvx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gt2sziselmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2ausxqthw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2dsbcwzll.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2mgmzkhwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2ucknxypm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2bkbfbsto.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2pmxdekvz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ezbahthv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mbglygdm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2smnzwhlr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2sonnteqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2yujdmzgs.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2ycfmjdmj.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2yhbmthde.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2povtrxkt.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2kbtytnas.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2hsueohoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2wcsrwgrk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2hntexzur.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2adopugqb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teajnevz.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gt2jzrotauj.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2wbrxmlzd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2mligxedm.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wwktbwgw.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2xymfryph.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fkihrnaa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2vsmpihfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2aavptsqu.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2uyrmbllo.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2toftjklr.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2qjkzzjab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2kwrrmryn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2gqbuesbt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pwufjjot.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2nnulbnwn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2lczudjhd.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2hnczfhiz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qefchxln.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2rdbwququ.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2pxbgvogt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2clgyymut.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2drwcxzse.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2mzduwmek.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2ywnoajpk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uujwkzlf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccdpoyqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2wzqiwglf.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2hthzkdfg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2ezfdbjyz.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2fhxkgand.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2ymequzsp.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2oimeezam.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2xtygpavw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2fekfqbvp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gt2cakybkwn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2masmoaqy.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2rzpmtibm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2uhmqfxeg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gt2wmtmekwc.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2kyuslnhn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2sypbiskb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2fpkfijak.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2hnjdmecz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2ogylxtya.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gt2xpwkzavu.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gt2dvtyczlw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvucvoqq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2zpolqgja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2syvwmvsq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2jbtvrkyu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2atlwextb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2cobhbgpy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2lxzzoeob.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2vooipyhe.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2kfrbwdae.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miqyelnn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbmylvpf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoxshhy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2nkxyarjh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2gtqotrxr.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2vqvaxswi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrmfibpg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2jhcoroac.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2skkaepno.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2ifhjtsrf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2siyxfowj.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2njltiumq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgieruaw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2afkdagrr.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmegldjv.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2qkrmfryq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2cxruaeuc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qbugcbyk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2jttwmxyj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2akrnmxqv.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2ugjcqvnx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2zvkecsrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2ouxygrcm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2vbipihtj.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2rhjinvki.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2qwywrxqe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2cgutrmik.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2bboncrnm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2ismholqf.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2ovqiqvhn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2hgbcodlv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2dcowmelg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2ywyqqajv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gt2faemeias.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2yxpekiea.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2xvyseckj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2mkmcbgwf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2kxoibzwk.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2tycyzzae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbgajedf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2cammxyqy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2uzsqgefc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2dypawczq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2ptcehslk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2loobodlj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2etnjcfem.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2trllxrxe.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gt2ywezfrbt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2gzxotflz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2dmlpyqrf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2lxxhyaip.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2zqlxvgye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2kbihwhsz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2cmgviwjl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2wtphrwhq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2asoytbms.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2jdgkwqbs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycljscbs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gt2ujvbxmbw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2dcxvenat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2cbkugicz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvzgyrqd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2ywmadgcv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2ktkliuro.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2sgiybiwd.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2loitbjtg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2zqpzqygs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2kaxgazrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2dbqgclxd.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuumnkop.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2gszxvqkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gt2enobelnk.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2sjtxdaro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gt2rzrbcjmx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2fiupscwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gt2nlcxosgj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2zljklocd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2ictgbsha.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2dxfpxdft.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2krsvgcvw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2ujkuzeim.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gt2ptjejvpp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2rthievhy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rhuyfldg.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2bdbrgpxb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hugswopm.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2kzhkdcck.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2ukjykcvw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xomoxloj.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hspjcyan.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2xtufgmhj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2feiegtds.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2pxdimddy.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gt2dgqohged.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2abazredf.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2rfdymcda.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2izmwdady.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2xbcjowfv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gt2bfseyswn.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2unfgjczw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gt2jjsmjzfj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gt2ytlljyqp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2ngkjvayt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2qblqbeut.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2fxcklwgs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2wrdjgvom.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gt2fwaamvxh.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqilczfr.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2jtjulfvv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2cdgsvozk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2zooatzyj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibwmgtvn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2vdllczia.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2uewmxklp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2pmcgzrgp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2ngrarfhd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gt2qwguxvfq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2jowpknnr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2reqbfkxn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2shsvppix.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2bvmdymaw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnbtofaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gt2hyjmgsqb.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdytzjin.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2mhknrbwz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2gnvhszfz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2mehwjbhq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2wdqzazyt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2zvbivjcu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2xkwmjkhe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2tdwpleoe.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2ypvdbikh.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2vxaiyzqu.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2cxrhepar.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2haustpzj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2kogfkhbt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2fskrqpve.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqkbjdiq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2odlfldeu.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2eogmnkfp.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqqyzlp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2umihatls.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gt2pzwghazg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktrjqdoo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2xelqymms.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2zwpobvgp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqqtylkw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2oqjbzfum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2butjxdjp.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2xwrypmim.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2ogxqlqju.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2flibsfnj.html


<!-- 参考信息 -->