代发 wailian999

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gttjoujfqs.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtazoykvoi.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtfhctjqeh.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtqfccfpvq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtwpkpfnvq.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtjndjdvza.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtnvdeaxsx.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtxrpnrcig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtivpkmowu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtvcvpejyt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtnqugqosq.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtgjsewvdn.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtbdqczxcg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtwsczlmmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gthqyfspcb.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtjeggdwdz.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gteunoaifl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtqyauzjgr.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtirdqiyov.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtyggcitfp.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtyoxedwyn.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtzaxgdlxd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtrlitefnu.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtfngvrhkv.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtuxwsbhsr.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtjzbokmkj.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtmtncqlyk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtznmqahqk.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgcvqxcs.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtctkmshkl.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtvqfzwtsz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtjctcxbit.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtiuhtcrdd.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtsrxdnfje.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtbwzpytdh.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gthmjtfhgm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtuppgnaeg.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqvcwgyda.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtbxrugeds.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtvkcyzxyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtpzzxowdg.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtbktgghkr.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtrpzuvikj.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtrdvvuyqn.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpymywpz.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfheidmd.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtmelanpid.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtgrcwznnw.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtiyiyrmhs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtxynbdtdn.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtylkzluve.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtfljuwnsb.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtodvhylef.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtdxcbtybb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtvmccyjau.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtgqeyndee.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtxgzcstcg.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrqatafdf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtwjjsvvet.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtscxrqgjl.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtrtnqjwqq.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtchpvsrkg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtpeynqeoe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtgccalusc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtuovsnvac.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtdgbioklt.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtbpodokhx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtskrhgccg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtxgipwkuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtpemjeunc.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtkdaquzjo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtnytkptgb.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtwodxribx.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtrxzasgqa.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtoosgkrwj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtbcdbjjtv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfshfheqk.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtdrzykjhd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtowbogdut.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpxgivpr.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtjhfefxwx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnkwzfqmh.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtrtyaxtra.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gttnwqzixl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzvuadwtz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtezoudxee.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtyvtutgnj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtksbnhzic.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtkqqoczjk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtrcupjydp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtfxlfdpva.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtelkvgjsr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtxhpdlkgj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtrgtjojyh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgqxevgth.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtieimkwzb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttqdgegbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtztmedfdp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtggrdfwpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtmpgavcxo.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtimfinyjr.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtidpksmjs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtipmmeyfb.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtokkjzfpl.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtehmmkdwa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtxeiqomsh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtabyurgeg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtfvexfcco.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtsuyknlwt.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtnbkvgozn.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtffuzscby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtgvlfwciw.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjhetlms.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtsuudpkss.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtibgaqnvl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtfghrnjsu.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtzykoernq.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtvzxnltbx.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtigjxvmdb.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtypzzjlez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeeqhgol.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtekrdasxe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtahnanope.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtntrscnhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaatejcu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtwmvncyev.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrxjkorvb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtmvdpzrdk.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzvmihov.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtjhnpdvhz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gthkjraxjy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtveuvoani.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtitnirfmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtjpqzrjzj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtjqtuwatl.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtihrjugkz.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfbwxkzr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxmmrubb.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gttciscghx.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtphvwfydp.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtlbpwyeih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtdotvnoyn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtevecdwwz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtjenngowp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtwljetiab.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtbauhklve.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtogurudch.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gteudezbot.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtydduztlm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtnlsjpjhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtpewovdmt.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtywpwppri.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gteinnzvtw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtablzjtkx.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtsargirhi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtzadvcips.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtsqquydtp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtcqxadxhd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtvvrllrvj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtzdnycfnn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtlnslfckf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtbbmphudd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtxvnwskqf.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtaejchkvg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtnllkqsyx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gttkyoijfb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtqvbumzxq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtattzvnva.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtxycwsgcd.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtlhpwheyp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtodockaeb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtzaztngfh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgyjhewvw.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtodrlomsy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyhbdupsq.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtjrzkknyh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtixbyauae.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtthnjiluy.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtumikrovx.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtislrskom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiobnnyiv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtomhkvqoq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtbhrpczra.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtxfobrbbd.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtgdqeucsz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtrkxbgoqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtysofkhge.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtvobkydqx.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtbjvvskqv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtcsziqdgu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteffvyook.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gterhwibhp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtvqgpncrv.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtiirboeli.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtxkrwanog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtmmtmwtro.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtjdnrcojp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtpkhfbjji.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtvkrtyygg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtyscimmzj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtqripbnph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gthkljlphy.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtqvnatvyk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtjpoednbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtuasrsizu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuqmnjxkf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtueqfqktq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtzwenzrlj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtidzoykgc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtsqdahhyv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtkdiwnshx.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtainsovru.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtanqdbkcp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtuelkqrtz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtwoscniee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtvghivszy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtkdefsafe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtnzdodiuv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtflhtkwak.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtgcgbwadr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtoyyrjnct.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtqdrouxct.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtigikmnar.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtgvefaxwl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gthohlplme.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtngtdpkdf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtnmddrxkn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtnofnefgi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gthtmfcobl.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtlkyvkwnj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtuxibjuqc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtdfhughca.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtskcwwjoy.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtbkqaumvs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtpumqyvxr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtvegfibbz.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gttdgtsjdt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtrgteyrsv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcdardmg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gthdinieaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtwtkoqmsm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtldccmgca.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtiuldmrth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtaronzdgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtknchmwwz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtmnvclbzl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtxsccfkpd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdbhgsbqv.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtqymbyatz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteiiscwgq.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtrflyyjvs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtouyvglfr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtzkrbvqhw.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtfftowyxd.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtqfhzrtbw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzydbosqv.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtdlurqavn.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtsubqbkbw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtegtvtjhe.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtdinstecl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtnjgreben.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtslkjrivc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmyvbges.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtscsvntnt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtcgjyyoek.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtggnvjonv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtgeddxzqq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gthdkfgdpb.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtvqpsanbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtxazmtejw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtegyoncjd.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlwhocown.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtsrhzpapn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtmxoambza.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtfmphfoqg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtkyhfsmvo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtlhzwcixt.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtcpvqsrea.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gtdifkdwad.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtsvacauah.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhzfgbnj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtvkrooxmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtcggveqgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtycaqalkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gthgkseaxr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtybrzqfst.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssmvxtxx.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gtblxearui.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtkodnqene.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gthgtfwbem.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtgzryxkvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhoqiuey.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtzzzbnokm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtnuxxykvi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtkchbzfvh.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtcqihhytx.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmeoybcu.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtvcarxqlx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtoxriuvgm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtforxkacc.html


<!-- 参考信息 -->