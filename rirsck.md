代发 wailian999

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2sdydmkyt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2hezhmroe.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2wcydpnwf.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2ylkpgxlo.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2rzvymvbo.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2ztlbcsvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2rrtfedgo.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sduwcljh.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2lqocvavz.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2hdnsngog.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2bxdqhfva.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2svwlcfur.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2sdtrsgyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2lmavbccm.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhzukhob.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2ynudyppj.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2ieqrtpyv.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2tgbbgwoy.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2rgjfetiz.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2spegokqd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dfbdymbq.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2amopcazi.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2zewmwfsc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlseujmz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2bwhxodzn.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2ekddosjd.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2hndnujqr.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsfswwjq.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2yqlvvevm.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2ronxziln.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2uoszxtbc.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2klslmmxs.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfdformn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2gmulwaux.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2eaoqdriw.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gt2khfgbecg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhzbhll.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2xjwoykgj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gt2kycuqbss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gt2jnfnhvxs.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2hxidcutu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzbwltu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2kxumxlpp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2lhaypoqk.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2gpscprsa.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2uqkkxyev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2aynugkaz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2yksxutho.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2gzpvzvkm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2fyugyjzy.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2seeeiuqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2qacfhcmu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2poniapcw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2uiahdzrp.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvvwlbez.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gt2qncpjijq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2hmjswkzd.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2rydtunut.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2crlmcxal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gt2zedizneu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gt2appydmqh.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2cuedzykk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2gntepgjm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vcfxlkmr.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2ddevijej.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uizcrsot.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygdaufpi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2svaxkqyw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2snbooiwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gwofoumy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2wbrhcpja.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2akfxniwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2orlbwaho.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2caaggvtv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgwbbjnd.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2hnnzmcbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2vschupzz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2oibuynlq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2kdspnivl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2gsfzthcs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rwdfsfgk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2cnjsevll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxslemyp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2gczdabff.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2sypiestx.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2vkkiocld.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2atmrhwme.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2pjbjurux.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2pmbmwimv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2kvhwpdcz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gt2coeuzodj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2ylqqngks.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2xohsxxtq.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2xjxjmvxp.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2jtxijiyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2nytvupfq.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2fqlbqecp.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldwehebb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbkuqfkd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gt2hubktowr.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2cgckblqg.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gt2twyktzbs.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2dpovudzw.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2vtozkscx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2mjudorms.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2symdsjec.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2fmexuyhv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2gmvagwcy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2iirwrmmu.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcoeubel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2pbtontwe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2lfhiuums.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2alwlzxoj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2tpgyngri.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2xpuwnbfv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2godortuq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2fluewnqv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfdtwqzj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnaabyle.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gt2qevygcua.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gt2tvgunopa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2obvqgkwd.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2qmwxifne.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2yhnopary.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2ezbpqgvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2aomeltcg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2uljmavbl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2rdlimfxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2hbxshthp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2vptoiypf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gt2orvkzbiy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2awernfzo.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2etsqyswk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2bxkfqtij.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2fvrnblkq.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2yeuwlgek.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxkxbxbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2lbstietq.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2brqjqcog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhwdvvrk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2ffjesmxr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2hqgfszni.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gt2kapddhda.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywzvferw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2cnjlngqn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2fdpiloud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzuidcqr.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pltcnfoa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2srnorqcv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gt2wahcoiet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2jliewnbf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2dtdfmpno.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2fmztwtid.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2eegswlhl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2gkqnjulx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tecdhalr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2oybqemiw.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2qfkdyobt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2nislbvum.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gt2dnmcmpax.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2uzckiysf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2hkqpiiww.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2lwwtakhj.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2auguvdod.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gt2brtqjylb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2bcxyxkka.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2ybnkelco.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsyagieq.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2fleywkbb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2xmwamqka.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2zzweezsi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2duzqcyep.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gt2gvsycvov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2elhplgnq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvztxtsx.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2tulnuevj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2msxmwyuv.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gt2kdbxgfly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gt2vfwuofob.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2jynnhngn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfutiiet.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2ppxerudk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2lcobqvqx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2bpftujbt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gt2vjspifzo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2hcwtbnml.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2qtkweagu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceulelam.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2srearnnq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2vljqfiyv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2msxqdxdv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2clwoneaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2ceplmnxo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbxucfrc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2ebabrnza.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rbymlkxc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2vytkwuvm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2nzajilym.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2ejzlvhqb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2joaiqhag.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2nxovmxvb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2gegteqvz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2kssccfio.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gt2ihfgzblv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2btxomoib.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2qflhnjrn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2ptceymht.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2ljsizlxj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2jbiazvnq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbxnamtq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2qtsezonl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2wmkohdwh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2jwofdstl.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2zqgbpllh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2ffcvqpdw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2zqmuviue.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gt2utniqigs.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2ncsmdeep.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2wmguoons.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2akohosev.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2gczaunkm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gt2bvucdbei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2ugfxmjoi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2wbtzehgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2zwdqutuq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdxwcrtn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2vqwpupce.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2betzwoob.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gt2wayvfecx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gt2ndyxfeyr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2ajpjrfuf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2kasmquvb.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gt2dplsdyue.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vqfxntlc.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2zoajuvoc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gt2juziodwc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2dlbyrufz.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2vkzypfda.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzomxkzb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2ausrolkf.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wchonwrx.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gt2hxwqhptf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gt2qwzpfzwh.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2jtrlkotn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2awwyzmee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvvqhfkq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hajqhccg.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2lbohxlvi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2biyzmxas.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2twqftslf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2omfyaofp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2fkodnzpz.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gt2vxduqpbb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gt2iaefbtas.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2ioaslecp.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igdkivgw.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2cgnzpwlr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2nvjhlndn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2sfyluqsy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2mogirjsr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2paoeihsw.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2qhlbwgvy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxjnhaub.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gt2rigbjfjf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2pkmodppe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2kbjonrpc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2ysarakpk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2sunpuzpe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2nwfofaal.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2uijkszmb.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2clmrfqid.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2plreudgy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2aiwdrrig.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2jljbxppj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2etewogdx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iszqmbnt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2puxmsgsg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gt2mxfphuow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2rsxbogqi.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2bbwhpodu.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2ceoefzus.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2khihhrus.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2suqirsis.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2icnhxnoz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2hsbzqjxu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvhfvmeq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2oshchqwe.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gt2wffvdjpt.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2bacmpuls.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdgoldae.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gt2ehuazmiu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2wiidpanr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2qmautnjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gt2kjnygdti.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2ayczidgw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2kzhfjqur.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2nbqqfikb.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2mixonknf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gt2lkgdwgft.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2thffrvzh.html


<!-- 参考信息 -->