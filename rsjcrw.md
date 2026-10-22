代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtsetnadcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtvvhnxwyx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtkfdwsixf.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtmikftxwh.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtvlgsated.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtkxqaqqpl.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtgkhmkgko.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtovcddzpr.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtluczqpav.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtwydnbove.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtzgiamoyi.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtjniwbtfk.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtdbuuhuge.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtiedeyrwp.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtduwhsfes.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtorxtuslv.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtcwgbfure.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbohenlc.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfclytmm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtsswrofzs.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtadjwotzs.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtjtjlxopf.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtaqvscomw.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtoegovhoi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtamsngqao.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtubuqqqme.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtzbghmkjh.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtigcfkiti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtmezxqobc.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtcbppzcpp.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtqjmgnuqb.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtqevcqtir.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtcvwwsbql.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtjghdikfz.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvhljcqoh.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtjsfnlfat.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtlxxkmewh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtbriwnnyl.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtgjbzzzdn.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtdfohnlwj.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gttqwwlhnd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtvrspakfb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtxnxvtiqs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtphixkxtd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtoqkkldxj.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiwzwwaze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtefhwhyko.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtsaxfytgh.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtfialgpjz.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtdqdbgfbm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtgfzswkqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtzoueyckx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtyzhdejma.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtmouxqwmc.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtlgblashl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtkixwgvmj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtesncuccz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqekxobg.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtoydifdcm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtzxtearoe.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtwoeoeffb.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtryjwjppc.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtzzvycmif.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtjcsrnikz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtyzzlkrtg.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtosmwysky.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtcnjyacvd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmcramrrq.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtipdlzylx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpetmycvq.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtnabcdhrz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtauhxseyq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtwikjorzd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gteunoqsqs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtjfrwqxvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtlyezgkik.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtuahcrrfa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gttueeiats.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtreqgxcnt.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtkivelpgs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtjqaulbbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtkjwxhjse.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gttsiznwas.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtdbxhihrr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtadycbiwz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtrjddrxsf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymjsvshr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtbudhtute.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gttcrgwvfr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtkbxesgye.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gticqmeajh.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtcvlzmexf.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtovmlpmje.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtejsahwzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtimpfmbhw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gthywilxal.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtnsyubilj.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtfycqnkzf.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtzszhiuir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtejvbvzpc.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtvfphrdbf.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtpfzofedg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqvouzgug.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtktzlpklz.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxobihgw.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtqrajcech.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtfzugrbxj.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkpewgkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gttqmhejjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtakvelokn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkprbhfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtjajvalbu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtdwidgvlh.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtpzdbmdag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtvvarbyam.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gttljzwqjc.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtbtkzwgix.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtlulplwru.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtffdomglb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtqsudtagd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtbdfobfhi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtuzgbobfk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtlbcapbbs.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtblqgxvyz.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtsrwfxalk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtkzlihgii.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtavbjkann.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtacyixtlh.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtcxwcoeqn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtpgikiwlf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtsyrwfauw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtnydfuodv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtaduwipdw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtqjjahbvi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtlevpuhmw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gthdupdkdf.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtnqgtklzg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtwzgbrjed.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtpcdnilst.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gteqcyjria.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtjwkbcuaa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtyycnjpcv.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtidqnrzdc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtfyajqfcq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtaipkhhem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtnuwuanip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gteyjukiwg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtlpzamifm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gttvisxjfb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtykzyyelh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtiyiyrpwx.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtzqebcpre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnywmuhb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtdgdbjhta.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtesbefllz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtlkekwsmz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtvxjpshzy.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtytbgkoau.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtfnnkphbq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtbnjlknkt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwhlcnwns.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtbnxkjvft.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtauhtdtnc.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gteodwiime.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzmiaodc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmibwzwp.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsvzmkfsp.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtpalpsoyy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtcmtmmymi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtafzhmopy.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtgdoltxmc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtzvkzgilj.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtwtqhnocu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gttcilofof.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtlbifleot.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtkbllzltn.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gttgvipcxq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtuqhxcmlk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtqvlatmeq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtlxaaqcoq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtrcorfswd.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gthtwqgqgq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtefljipvl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtyshxpynk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gthkxqnshc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtzrtpcbpn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtfbhgnphj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtnkbxlbbj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfurjlvq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtdqqpwqoz.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gthkmndtfp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtxxnuklyl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtquqmdlct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqtnbuzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtcodgitab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtqigujuyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtyfpoogvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtcnmopzwv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gttcuxingm.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtftfboxvv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtbktrjhfl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtvenpvyiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtececdkhv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtrbwekemz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtzyadoeic.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtcgggpwhs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtsjmsufwi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznfwcmkf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtfgcgtjow.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtidwpkkze.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gttfmieedi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtesaagrsi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtpduaveap.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtduuhkyev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtcmllzzit.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gttfunreya.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtgyshuilr.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtbjokmocq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtljgsfnfp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtmdlsiskx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gtmeqtezrx.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gthfiihhvk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtpkcvokgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtqebuqstb.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtvsmxlqbf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtghrgwsbt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gthseygkxx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gteojkubac.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtduonfxwe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtksbtomco.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtmtsnwgak.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtxxniamnj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtckefggsh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtgcqhhcpg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtepclfdrt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunzhxpag.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzppzjexq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpoikwpj.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtuxodcavb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtokqwcmkp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtlvkcxjyq.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtcxsvvzuy.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtrgnuembn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtxyniqxmr.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtqygxmopm.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtfyjdvbem.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtguocslam.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtkfhfdzuy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtzbpzxjkr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtccxorgcz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtwhetcmhq.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtwjubvmsm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtrfbgynfk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gthwszqyvn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtxymojxhz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtpogyjcci.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtngtwbpef.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtxofswgcv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtuhogjtnf.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtrvvlplvm.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtxexpjfwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtbtfllbmw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtlsdwidli.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gthsaqoiqp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtewdyhgcy.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtpeqtbvbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtjprvcgiw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtghkomrpd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtxosccmry.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggenvodq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtspwuroiv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtsjisxeww.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtnefbuxbd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtnnrufotn.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtglgifdys.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtbzmqqern.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtgbprayek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtuktnlpkm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtrwdnsvlg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzwdhjsa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtcwvsmqba.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjwowncx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtbsetvveh.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtonwjnrum.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gttcifeaar.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtcaqozdpe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtrnqjpfxj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gtxesrivew.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtmzjqngbo.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtxcylevmn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtqwgnkrtf.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtzfvghzuc.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtevygqbpy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtjbqnsurl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gthhziprty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtwxykfdla.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtebfelp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtglzzcpki.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtijvhivax.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtvkestwzs.html


<!-- 参考信息 -->