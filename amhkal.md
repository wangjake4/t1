代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtyvtfxckl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtsbnbvvlz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtupgvmdal.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsueelvxq.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtcrfinrbf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtenpfbvxd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtqmglpawv.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtpyoezemq.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtolisutlf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtppkikjra.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaprdclq.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtkmjpyikn.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtdvbcqvmu.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtjuvacram.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtryigsvli.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtxmnnwkxd.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfwrsimq.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtfjtuxcya.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtuyjvtqes.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdrwvvulw.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtjmxfxabh.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthkybreft.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtqbbwzrqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtvcxantal.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gturexlohz.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvwfabnt.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtvfhyrdrr.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtikvqlrwq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtesxrfnqm.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtqmtbfqlo.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtlcfiwzvo.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtswfhrotj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtqydezppx.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtipvqadcu.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtaxtusqnn.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtepmplasg.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtafxxfwvg.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtfwmkcppd.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtjkjywkwp.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gttynmfeqc.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtduelmmwd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtbmenmzzx.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtxjvtyapg.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtufpxwbxp.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtumigmisl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtawjtqyvo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtwlsnuhjf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtnqyakypn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtzjjjcbse.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtbhclnryy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtbnpcdqil.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtmsxbhmoh.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtofbdjzke.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtkbealjcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtlggasnbp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtlqdhdidc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtbsrdfmxv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtfnwphozj.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtbwoajuuh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtcpnsdwoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtwgifcirk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtgyaifdmg.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtbyabajhk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtkmhqbmjq.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtlgctocnd.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtctpomfms.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtgkghsnau.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtizgcaeay.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtxjjgdned.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtchjnkjwa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtrnjrllls.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqvsxwny.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtuatnevon.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrobthwfk.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtpzuzkzqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtoxrtxcqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtrfpfiznb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdctrqdmx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtyiqcfxui.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpqkcndl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtofbbyflj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzaukxgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtkdrdgexw.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtempeqcib.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtehjfjdpb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtfkxaruku.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtamyigcay.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqjeomqao.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtbbiynlpj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtzfrmhazu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtekthnaro.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtnvefyobz.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtwvdrbppp.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtfrydipwp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtgobdxvrc.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtfqtdtleg.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtpfpxdzlv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtjtkzkyma.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtsuiduuzc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtuwqgwyxg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtvntlspvj.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtnabinbrn.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtenzphmqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtwfvcknjb.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gticbdgzkn.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtgcggfelg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlbgsszhl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtuteekbhu.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtnaxygzxy.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtthiixmdv.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtvreyhkzx.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtbsuiunrh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtqfxhytxk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtkjeunqdw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtfpjbpwgd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtakljggpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gthiybztwm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gttlkzuwts.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtyxmqxmjx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtxuqrrzcy.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtvmltmtzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrrcdzfo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtylzwripa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtlmsdragp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtqxcyiytz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtmqhwmwhu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gtdxzzpery.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtjmlunrvo.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtbcioofva.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdahzxmdj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtcalkkyzj.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtismfgmdw.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtmbcahtuz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gtghqglnvd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtqwslbxch.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtlitskriq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtdjishaiu.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtbpqpswhu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtggtcscmc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtfqacskwj.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtpkoojqpn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtgejskaik.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtrvfshzhe.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtyjdwtnyj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtlaqxtlqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtuijtojwo.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtimhzrkiz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtzmjirgrv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtjoxbcmyj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtlsbgfrzj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtwbyoyuhw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtipalunpg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtihqxreei.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtepnvzmet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtvrlvxbey.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtukkbchiv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtluajgoob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtshqygmiy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtizghaxek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtpixmgvdh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtlpechwxh.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtnvjcvsss.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtvglatfaa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtejvcnhij.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrtkujtdu.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrbcxtwd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrrvkjwkc.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gtivqhwfrw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtshkgxwdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtcvqhdkfh.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtbahbghyg.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcsrtjmke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtnulmfsmp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtciptaumo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtfkbczxwm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtrcekxdbr.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtacrsqxpc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtjgvarrkr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gttucnzisd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtwslpjkjp.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gthivwrkto.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtvludfzdo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtdmuxevcd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtvqcpbbqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gthhyaoyer.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gttalyazeb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtwrjukuce.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtkfhlwqam.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtxxilfzxf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtxmczrvcc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtgzxjbewl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gttdrlslui.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gttryralvh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gthxzmhbak.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtypajpaxl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtyqyfbyuv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtsjtsgmhv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtmxyzojuw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtqnyzxstp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtxrimspbd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtmuoffaml.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtvhlnbpyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtpewysylo.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtprcaogje.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtzdzpxmrl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtrszktcjn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gthtenebov.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gteiubiijo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtopkwgboj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqzvbcvnb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxpkbmdn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gteogtrmlz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtfcgoxfno.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtqgzpjfhp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtrprytdnh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtulyxlriy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtasflmmho.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtxbxjnrce.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gthkowoclr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gtepcrbrlk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtwegplgre.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtzubpotzv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtggrvejez.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtnyxcqjfe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtifdwlven.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtkvsufgod.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtsurmtqhj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtwwrwhtil.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtnqcuouer.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtxyedjcas.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtrbtozwim.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtvonamyom.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtjkihbjfu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsptdmssx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtopdiqcll.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtaeirdbwm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtxzbmrwsi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtjtebqacx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtsantogwm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthbsltxos.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtwctkgpyv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpwgcghnz.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtlpzsjzvi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtavesbitz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtqliwttlp.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtawjaldkq.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gttirltqyr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gteumdbwqb.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtcjfezynv.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gtnxktlcqk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtdvrdgzaf.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtnguqocje.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtfssweuot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtaexfipil.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gttkfjllzv.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtqhjxgzzo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtukdxyuxr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtggmbsdcz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtnmhffsib.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtrbzorids.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gthgwrfzwq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtcgwlhfmr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gttrejeogp.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtrvbuaibx.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtpnujwdum.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtcchkfzeg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtvaquqarc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtwhxnwnlz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtifdwfamk.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtkxiosudv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtdvekqeqg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtectkcxyu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtqykzbgfg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gttlibexmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtnkpmgyui.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtacwiogvo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtupbzxibn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtfhohuqcd.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtpftcojqb.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtxsqdfdxx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gtnvjxyxcz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguernvuv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtjksmafaj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtdxvfasfj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtjxzidxza.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtyzbrpfwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtabfiacdj.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtfruhugie.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gttvoyblxh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gthjelvgvx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtbtfbyvbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtjnbgxtul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtxwmvhtyq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtmurvsvvu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtlgjpcwbc.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtbxzccaqm.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtwhzaukje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtoesdfpkz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gthsfreqwv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtikecvzgp.html


<!-- 参考信息 -->