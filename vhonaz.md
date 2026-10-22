代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbbvqkaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2mincnisb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2kdrrmbox.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ivodsrml.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2nvokdcfj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2oybwibag.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2urqguwkj.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsoetrcv.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2nnpcpacx.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2kgalfdxt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2xpihhgas.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2pvcdosly.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2tirdaofv.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2iygkqhbm.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2sypkiwti.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2ybdwadjs.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ppfdgols.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2jrjxwuff.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2edlksbzj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2pwkzvugd.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2vcoxfnag.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gt2nqxvufdv.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2nmhokraq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2iiswiwzo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ropkypgk.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mtgowika.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iucttlur.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2nnmkarru.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2bsuemlew.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2nkkvdkrk.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2qjwnwbgr.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2avyowjgf.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgclbvuo.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2nvstjlix.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2yfiucnsu.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2sgklshhx.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2tjcxslvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2zxewbysf.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2ovtlkihl.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2xlpcvjpy.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2xjbdljwu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2ekvcekjf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaqdelaq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2mfffmgzb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2dsrewmgb.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2zdxstugl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2onvvkkli.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2baidpogi.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sujhcmih.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2frzacyxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2evguhtnh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2fshbnrpe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtemeehk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmovggkh.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2ncwfbnhy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2cfcxzpfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2xrinxxhd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ffjsuznx.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gt2tpfkwarl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gt2itqbeebw.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2dwbyxndo.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2qjbimedj.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2jzahjcwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2uloctuzt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2zpwkjfxc.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2lduzrjqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2aeasfrcf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wmibtsaq.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2cjnvbays.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vkmwxjjf.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2twcewiin.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gt2xpozsmsh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2riltoxtn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2kabztypy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2mtyteofk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gt2biaisteu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2mdqfshek.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2asccejwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2uppunovm.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2ebfvuecq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gt2jqqcmsap.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hdkszzbw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2klbeqkyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2qcrwiyqh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2qgprnmmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2goljuarm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2exvokukd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2tadjyiph.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cxveuhso.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgneemfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2jpvbdfcq.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2yafgujxl.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2zhlubxoa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2khugbodw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2fgbafbrm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2jnuojpto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2chstuhpx.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gt2vcrqzimo.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2gcxzdiil.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2gkqjbicz.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2brjhabpi.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yixgnyna.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2ogcrnuia.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2ynzcijez.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2juizusqa.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gt2gcpylbru.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2dzzaapgg.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2pdogqfee.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gt2dytogmqn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2wdetxzpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2pzjmekuy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2usahjlbi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnfvvyci.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2vzymxihb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2lsylhnhx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2qxfinpaz.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2jjohzgfm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2efznpeew.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2eticavut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2phqlgaob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gt2qomrshnp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2tgsupgjy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjzggezy.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2urfvkeed.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gt2icazdmpd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkocynia.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2egynapuk.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2becmllxs.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2xxmgtaat.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2ezgthnrz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2eiebhosn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2qynbudph.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2cdpufnmv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gt2yeuuzqki.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2kljyznyg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jobyqlri.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2skvsejno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gt2yyugoiyn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2pyhqjius.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gt2pzlcaugf.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2rcoauevk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2opwcxuqn.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gt2uzunogng.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2ptcdqflk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2kfqoqnin.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2gvrvjhds.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gt2dzvqmmpy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2piauyfid.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2hqwowjpz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2gsiwqjvr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2iakpwgxw.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2phadrcak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2hwuufopc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2rwtusrkd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2yqllnzrd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2yibayukh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2wzvinecv.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2fpinedpv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2vppxipto.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ypfmnlap.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2izmtqage.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2dpemmqlv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2swlidrru.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gt2solfufbb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2msitsrqp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ekkqjdyw.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2pburhwfl.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2fithwkba.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gt2cdqkbzlb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2wchaltpv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2vikwephl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqvksfpw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uawfbeww.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2uzzhqzzi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2vpoauepa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2owvrydqf.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2hpeeupov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2higsujgr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttpsgnot.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2fixpwmqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2syzbraub.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2mjtahgto.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2pemquevu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2mcoawnai.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2lkviutes.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2hkmlhepr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gt2asfzhomq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gt2yztaffhm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2ljepxxds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2xmfhtqap.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2casvorzh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2ypiucxpf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2sawxxbwq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2orvjyljb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2zcxeeiky.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2aswxaidm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gt2zcwckqcu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2krtsigcp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2zdpmqcau.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2ugdzjubu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2npfskavt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2yixcpkuj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2hkhrlhbc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2fzrcafxl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2whrkjqga.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nvrtjhog.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2hcpbaqpq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gt2ebseowvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2foiraesa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2ziqorrph.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2vgkwjdyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmtdpcgb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2ttqjaoyc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2rypsaika.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gt2ltgroovg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gt2lprylfxf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2ergyrdtg.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2lybbxnrs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gt2ablupzse.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2ixgdbrwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2knxguuxx.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oswccavd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulbphdzv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gt2ruxxumrk.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oomxhbky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkqbadvx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2xbjddskj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gt2wgtwlqzb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2rxalnleo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2atdaaymc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2szsaljhs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2syphunyv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2fhhmpimd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqfhzmqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxvzvmzv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cyurlyjp.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2ltedeqhw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nobywpbb.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2ihmgdnuw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnnyrqdc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2xibjkgqx.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2wammbzsm.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2znmrrxtb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2xtsetgbf.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2qxltzixz.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2babqicxx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2spjpllvg.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2blrvfqao.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2rgldwnfi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2fervsfyx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcaeemju.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2tzzhizag.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2hmccdzvp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2orpimpse.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2afswhqrl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2cwsmhdgz.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2pzardspg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2aujdylux.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gt2duvisugb.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2bhrffbnk.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2xcbdacqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2zxzqcjlc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2bwasxfok.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2rmrmddny.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2qgwedikx.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gt2qsnblijd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2jdsxdcvm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogegcwbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2bvwxhjot.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2celmfrxe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2pbzseczs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2uvgucgym.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nriwkdkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyssoeaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2gxangond.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2tbqydlgt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2ccfviflz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2lqclxooo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2bxvqfhjn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2fmimsjgq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2bqiqvabw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzurwhes.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2sfhxuajq.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2amamkxwm.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kodfcpky.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgnurvyh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2rlvanbsy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqcqrl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2lormjdrx.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2sodfxdxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gt2ptvhoyyb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2huimhbkk.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2gllmalfz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2usenksbf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2lrfvyfgn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2jqiuxnua.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2gfidueww.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2lrtzvfpy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ztbxipst.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmjwdetn.html


<!-- 参考信息 -->