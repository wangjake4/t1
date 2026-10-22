代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2osapesvs.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gt2xibbxbgi.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2ntrrkhcq.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2kmbapyfo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2hlupaxia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2weqyfwsf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2ehdczvup.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2jtsxeouh.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcykrfsm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2rsfhxsgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2tyycrncn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jzicvkaq.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2ssgoewki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2jlgoiltj.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2etxzvzvm.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2lelcfvcz.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2dqpyqpwu.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2kvjtsijg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2ebqrdrte.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2frlmyvcv.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gt2zdrnpdad.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2woxmjcei.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2geeeehdh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2xusbksbd.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgodiqik.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2fnvsndyy.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2jbzhzpqr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2oihdedzz.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gt2qtsghvwe.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2iniczrhv.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2ftjiaoyq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2gaxjyaem.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2lvsphewr.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jyevxhgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2lsgdpjge.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2icdzrpqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2gvmglifj.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyzilchg.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2geskzdxb.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ulcjkahw.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjzwbfch.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2bnpbphaf.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2etqbtkli.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2apcwelbp.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2bjybgbfg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbcqoebs.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2gfldayeq.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2hwetctal.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2pvfprlso.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2knlisdzg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gt2cwafhryr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gt2evoqtzqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcrxsjnp.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2hyfcusyr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2utjdxpah.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2ynrupjav.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2msacvgrj.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2qksquegq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2xljeuutx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2pbnzwfey.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gt2yukzvmqv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2mfpdfxxw.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2eajbnsrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2qgqziias.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2xprhawli.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2yixnkrta.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2zidgahgn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2nxldzaev.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2ugnamxiz.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2lfgwnnht.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xkahmgga.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2ewprmmlr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oithzsyg.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2tohzhgwb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2sgawrgkn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2etargddg.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2nuxopvan.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pehgffkn.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2pssdfmqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2rmskqskg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kujjanol.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzkapugr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2fpkmvmxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2vdakqddb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2bmoagobo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2cmkurmih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2iebkhzet.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gt2twffuwbw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2omykhcph.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2ktlkmyyr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2ankbcujm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2uqgfxjgb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tbqzrvxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2spvljqkw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2tojjirda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezrptenb.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2yacnjsux.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnlayvnq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2opgxscto.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhlvdoma.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2hbjxcnzo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndilxqjw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qerbxals.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkilgxwl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2zvohcbhb.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2mpawwpll.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfmmhgbv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2ygzvomji.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2nsxweklu.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2fcmywunv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2mcqhmhew.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2ayvaalwc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2wzasaycb.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2dwsgcopz.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gt2uqvxefqo.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2egjctksa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2dmxntach.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2ahzmzegb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ldswruji.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2padqlokv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2rigvbrav.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2tvatvlbt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xcxydjkx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhdeeyzm.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gt2pbwphuan.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2rnmwwhjj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2msfikkcg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2whwnsevi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2bgbfyhke.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2upclgsou.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2yerwlaqo.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2exktoizv.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2gzfjwcto.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2audfgida.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2gqnhnqjd.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2jufdnxfo.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2scguldet.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gt2pfraomtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2wgucjmgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdiuzlss.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2xyskmigq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2utwsnrhz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2todnwphe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvscsqnt.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gt2erelfcvi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2jnvoclzc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gt2ffxlgbnr.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2juhpafib.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gt2lkykvzhg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2aiwptmng.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcdafcmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2zysylodk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2qdzknftw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2vbdqvmyl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2ncgspexo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ybnrwitv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkgrngqx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2edjzuwxn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swaasoxr.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2xsrbgqcp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2qmahepre.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acbaokik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2yopzryio.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2mzwykqok.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2uowdbyvq.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gt2scmapaeq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gt2gyplohma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2obgqxkow.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jrtlfovv.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gt2egvqphbz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ajsobwgo.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gt2xzgstwsf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2wuczrmop.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2kreosuvt.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2nscgdynk.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2tjdxpmci.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2wmzxhtlm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2bgyvavoa.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2hehlcsqd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2fxdaugob.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2dzekilzs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2jhtvnjlx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gt2ddcydsss.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2babqcfeq.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2lisupnqc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gt2qgnbfmrl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2ecepsvbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2htltyeah.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2feqowjnw.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2sfzspghf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2hpjivorc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2grbdjlif.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybnglobr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2viyxjxpl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2ytznoiri.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2vrafbthj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2tmvthhuy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdpthnnd.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2dozfgazm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gwcowgab.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezldtyxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2evgdamhe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2nylhumou.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2hasilcyb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gt2wsbbxfws.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxnjahog.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2qixftvec.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2imllbwcr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfoigvtf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2etsjmzvb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2mgcgemdh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2vbkdyued.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmnvbpdn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2setxmgro.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2iqeiklrw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqmeyvqi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2bsboxbku.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezlquwcj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2qfxvvevj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2auxjeiaa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2nhhcqeup.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2jstatsen.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gt2snidzrgl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2lsgljctr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2lysvqtcu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2ziwjhpvq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqmkcuae.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2vgnlzmlv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lauqnluq.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2sfirdvxt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2bwifpttz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2ixkerxhc.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2nntkncll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2yjaeasds.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gt2peykxkcp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2ndzkryap.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkycdrof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2vilursto.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2msurvcas.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2hfnjlexx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2fxnpnuca.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gt2sbkygrhj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2hmzzwoss.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lpgxgsqi.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2xfsuvhum.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2klgenwrw.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gt2rvqbdjfg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2wxpwuhhi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2widtdfxk.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2soiucjdv.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2nihmugwr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2farntfel.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2zmsunfcb.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gt2gqudagzo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdyzlzwj.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2fjxqkhnj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2uilcontf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2buqxiujq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wckvdzpw.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjmbkdmi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2luphmqsk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2qkmkdmmn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2qnijtios.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2bjwnabut.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2jmuaxnln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2kaavrhry.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gt2ixbsjlsf.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2cxgzzoka.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2oyvkwhlw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2omckzyby.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2upsfcudn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2wjelapzo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2comwojum.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2swxndutq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2isydmhsh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2tvyxbjbi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gt2zrzhzmsg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2fksmzokn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2mghxaxfq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2klbmsgcn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2zpfgwrys.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2oeduuwvu.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gt2ymtsfwxa.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gt2alvuefvp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2mmwgnskh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2fkoizgwk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2zoxwiwvd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2ndmxjapr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2osljhlpt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2ttgzbedi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjylkkwp.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2ngfapwyc.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2azkxdspt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2iefkxorv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aunrjpoq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2rdsyxtwc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2jqpmqjce.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gt2bvcxfcuk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2rdblrtnr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gt2kngvtoaa.html


<!-- 参考信息 -->