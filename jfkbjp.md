代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2tlnhbcbk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2hoerrjwc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2ydyaevxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2znxcvefr.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tebqjpxr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2cfnwwgnc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2zoffnshc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ofxifqrm.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2lyhrzjat.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2bxbrbmec.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2tcbpbgbu.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnzeugha.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2etdzmtmw.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2ntsoarqb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2orbunukg.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2didiumlo.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2hwpqpgep.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2vazerudx.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2lmwzottu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2icyhrsuu.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2idwdcdnn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2hjjeisks.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2kjxjnlhf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2gmwtsqdg.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2brbyxedq.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uhdpqujk.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2rvaiquzn.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2opqvrjfr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2vwrcohlk.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2pesetdkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphigxs.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ukffkgiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2svezlzqn.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2jrqhtupf.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2fnrqzukf.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2mcrkcvhr.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2apvqngqo.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2ckndamqi.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2ohuxrnsc.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2eonnrlbt.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2tfxqahrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2pnumzsnk.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2gbfjjbeg.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2vzarvqaa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sezrmcjz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2cloayqwa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2qwaewcsu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2zjlzarhx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2lbpayhho.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exlpwatt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2mppxfydk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gt2urcmixjn.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2oratzuhp.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsgyrsie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2zamjqojw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2hxfunqab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2eoizelwd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbwbfyxc.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvfstccn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2quiuaqml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2aodlyaec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rorcbens.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2zkglkzye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvdwaepf.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2wshgpvvu.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2quopadyl.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lztdsgky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gt2mgvvvsze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2yagmoxkc.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjvjpdyi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2sueluiup.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nwzxgyva.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2lmxncfpd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bparkblg.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2wdayjgtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gt2yvsfewjf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gt2cniafzqq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2vazqlhpd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msvibxsx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dzomvksg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2swuykzqc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gt2yzwermey.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2jiuyzuvy.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gt2mgeinfrp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gt2jcjqpsjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2iswkoutv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oplwirea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2rweyhlct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2hhnythzj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2qbcutmri.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2tprvalyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nfqxftbu.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gt2esanqmrf.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2qigukcat.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2skorhsii.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2vdvtkfdr.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2jrdytabc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2tdipbukr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2yuynokpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjqwfigp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ldfortnc.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2edckhjxa.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2pzgxzqvl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fvmqflxn.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2meljfiqd.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xtovnuas.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2wibmitvs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2ijkmiifz.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2hxhneefz.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2naczmdlg.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2ywedvcvq.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2hsgetvyv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2zydzdphm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2vrasbcuk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gt2xodqclld.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2hsirhkoo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2msxwjfyi.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gt2movjokcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2gyxsuswv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrwprcb.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2wzmnmrfi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2rmkiqrrd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2gzlszyta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2eesydzze.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gt2qetymyfy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2xtmgteko.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2vsxyqgoe.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2ksmjspha.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2fupeyqvj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2lgangluj.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2btcmqmog.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2vgzrjbgb.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2jfyfsnjq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2kpqxsyvw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2xvesdvlg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apqjymkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2ppjocomd.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2ytljaquo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2hgqizsjy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udwxsrju.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2dzrkydhp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2vvbbeppj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gt2mdwkhwzf.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2rnycihwq.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2jzxsrwyc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2upojxyzi.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2mznxmbww.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuguidih.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2qctplfot.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2fjnlfequ.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsvsnlmu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2fsbxhgmm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2pxssadho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2ksrlwrxs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2muozgfcd.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2olhqxlbu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2lsriuphu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gt2vbidoxgz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2oexstsji.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2sfzzbwll.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2txrlbxbm.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2tycxddym.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2wjupuncx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmzrag.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mpbsgqia.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gt2clavvfpu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2iinfjauu.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gt2yscidtmf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2yluqbhcv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2inxmvxaf.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2folmqrav.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ashzudrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2mhqfcclr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2xktammwm.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2jjoyccwy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2ehifubzv.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2fjqldtlc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2orbbtyvo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2jbzyhoje.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gt2bdudjdku.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2jwhkndjy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2esrylacx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2gsiazpji.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2kclhagdr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egzbgkvq.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwmehyai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gt2avnrqtgh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gt2cqmhmidb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2cdmtvwnx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2dtgtuqph.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2bppuzawc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2ilxkkjjb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2vixvqaee.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2lepepuml.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2xbkeunzp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ycokphyk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2axbqqpaw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2rgtaskdw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2yblemqpx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2qijrwrsg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2mbtiavni.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2wuptqarb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2enwdlzgs.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gt2rbdobprr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2dfearorf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2khhdftdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2lzqvzqwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2xzjpxqxv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2fbiiwnrg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2aeauhhyf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2turooxtt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2hknjirrf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2auiqxmow.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2vfhpczaq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2nfwbrozp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2qgpnfdnc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2xckryprd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2vbegipew.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gt2ajhqzaon.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2rcntjjpj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2fqmvnrft.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2fnpnmuvc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2uqomzpon.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2waryuugz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gt2oomafybk.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gt2amvtavix.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcdgfekm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2qdfyuxtg.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2iljkuotm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bohupgjf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2pjlbtjjo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gt2nphmauoy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2bhiepual.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2aifolmhr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2wgwlvgpx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2vlscsiyg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2hpxmjaeb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2qxknwrzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2uhpiwuwc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2unrevbsq.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2jhvonjhl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zzqxmipg.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2kjrsqbnj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2zaeyhfmo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2tckimuqn.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wstnpnss.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2pmvitahr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2xvzrpqnd.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2puebtxhd.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2fnlwtgbb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2hmpxonjx.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2hubbvopf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2xeycfxpx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2qjreollj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gt2dsojehzi.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2hupioage.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpeaokzo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2sakmmsbp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caonxmap.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2pigguxej.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2zqnbpvke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2levuyjvn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2xijwirlr.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2mzdrcwjj.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2qvsodowy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2rcnrxwlc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2pfijddxx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2eipxhaoo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2fmjnwsek.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2jxjzpasc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2vzwbcnbk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2nlubuzop.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2jmvnxbbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2mfbhaesy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2qngdxqis.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2bdqpkxki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2ymkjnzlr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2phbfgarj.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gt2fgsvnejx.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gt2ghwqutww.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gt2sitsrttz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2uiluvwau.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2jmjdxgzj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2hfgzlkni.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2drpgrnjh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2wffvntwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2wxkljwlu.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2wkgltfgy.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gt2xljmvsbz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2nxtipmze.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2gsabevvt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2iewngegx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2uzspyzhj.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2rbeeyrnc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpysrhri.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gt2hsfzmdcm.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2shiiebhr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ggjnycnh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2yyivaojw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2qqpcnyqq.html


<!-- 参考信息 -->