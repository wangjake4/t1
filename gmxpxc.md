代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtzqpholed.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtdiugvuro.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtjritohwu.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtxulayzie.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtovyamzcc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtlbzxakec.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gthsbgdgfh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtyvieraic.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtwhdmokug.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtnlizgyrz.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtwidtocot.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtoxtfzcfd.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gthtphtjtv.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtijawgorp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtivanqgzc.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtakkqnpre.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtzsdmjrjx.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtgioffdhl.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtjnhhydht.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtrvzhhmuf.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtooztwyju.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxrtunalt.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtbitgoujz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtdndpxvez.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtbgbbdsyn.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtlaxqkyrg.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtamcysirm.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtvauefnhi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtdqyzfyvu.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtnnvltsoo.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtydltgrkk.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtztybdtnv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtkjerrsdz.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtiztunrbf.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtogoxhucm.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtbmcpvcfd.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtdpfpzpfb.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtytxjvsmk.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtrpzrgmlu.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtfzslrueg.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtnujftnxd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtnrcoyybi.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtjjhprpgt.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtcfuwgldl.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtuyzovhqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gthjmwmmky.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gthrnzpvtz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtryimmzht.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtgxvtgscr.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gthunkxjqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtobsuhepj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtuhlgnwrq.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtevsjvvec.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtdjhmeybp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtaemlwtte.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gthborrgfw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtsiexfoyo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtszhhmdek.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gthxgvnobp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtlnftunhu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkqgtbzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtwrxqpema.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtrfvynsqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtdzkwhrkv.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtifogruss.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtevaepfns.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtugcbftsr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvvdhzvn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtgcyhfxer.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtgqdznmeh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtinnfhsip.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbvnljtkf.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtpnzgzclv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gteyomufev.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtrrsvhuzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtiellnoqc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtfzoxinpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtxgqgsnnd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtalqfngse.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtckkpbfbf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtwvfwntkt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtbqeqa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gthtcyhhcq.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtwjtmzglb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtyumpytqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gteiuzcyov.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtdidpqwur.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqquxbicb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtupygjots.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtiteguags.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtfmyydpdd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynnaaacj.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gthtfajzwi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtgaslctri.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtuvcgrbif.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtuhzomtyu.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtsrfoefgq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtvaylxgtn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtabojisel.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtucsjtrcj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtkoaozzzx.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwprpccen.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtwmvrfwjn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtyftveilz.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtrfwhpnng.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtksawfhnx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtxuqlsjay.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gttalaibtc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtvdvorrwg.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtljniqkba.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtdjvyhzpf.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gttwdrspgq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtgssiouqe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtkmnhufzh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtauzijmdv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gttowupdub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtmcalnete.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtjmwwulra.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxwoyuojn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtqnhsfdfd.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtdkktefzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkrirbhz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtkvfagblx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtdibugpie.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtextuqjzb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpduwijqh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtafrmlqtf.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtdxflzipx.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtrymyhhyo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtfjmejuyc.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtauprrdxw.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtsyfrmmhl.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtvccsjbnp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtqwjqyzof.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtzwctmxcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtnzrdseog.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtfwyasyzn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gthjkqzrke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqoyvsmk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmljaribp.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtuydgzwqg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtpgxjiufo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gthviiysgh.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtdhxogbtr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtxilfnfwi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtwctkjpse.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtvzppgaio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtvejtmtbj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtjtfmgwti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtcxwtaqim.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtdadexncy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtxdchvbbq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtveqrqgte.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtytdfqlhk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtsqosklnl.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtxcxljvnd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtsuophjhz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gteopqjwaa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtsrzbpbkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtnlzdnsvq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtqwsflomv.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtesxjwwqb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtcgqvbjup.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gthgpsrxys.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdizozpc.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtszhygihb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtizagatfr.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtqgjlbgxx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtqptnuqvc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtklibeyce.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtaqznxazj.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtvfhbsmfd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtpqagoovl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtcmcvmfcw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtennmzgsg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtwyzawfoa.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtoelfbxcl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmadcgzji.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtifycdmqw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtmsbgocsy.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtdbthflwm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gttrpbmetv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gthbttkotv.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtdmqpzygh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtmynprcbo.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtsfuamosg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtqvktewds.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtqxubemfj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtqbqixzso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtiiquvzuj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtuszbqiwz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtzbarhdrx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtdojvscng.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtuysywnza.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtvfmkvmsq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtigdkhasn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtbeczcpnw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtqndkisfi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzycejdo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtfizrdwcx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtbgngmlwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtpinvgruj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtrmfjctqx.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtlfofdbgy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtzrjevioq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtuxwrufdr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcbeftka.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtmrwrcccp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtrqygueec.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtsuvzbxij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtpzpgaklf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtkwuncntt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtwzmdgnig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtrzgihzam.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gthjekoxvh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtmhsbrvra.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtbtexqauv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtacegeklc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtubhhakca.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtgloeuaxk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtrccrgtrc.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtvdfggyzz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gttbfqbxod.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtlerizjtr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtilybdsvb.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtuvegvvta.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gthoqrthtc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtbjjpvzze.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtrygahjgk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtvlltmvlu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtdbgbwbwq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtooqyobud.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtpbaqpjkl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtbqnvofoy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtagzuhpjn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gthoijzjwz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiflhzpl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtuvhookvz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtvkqxjlla.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthmsaiutu.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtqebpjpsv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpgntolvj.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtpgvooahx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtlfchdmjv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtkvkngypr.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjntuiucx.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gthlxgtefa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtiqakdckn.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzcsbmqv.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gthqoeacxk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtjwddezfq.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtbwhhegpt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtwmvbeygo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtltxjrzmv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtoekbqenx.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gttwezndvd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtdyifjfbs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtkaffszuz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtgkftkhsl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtwriilwmz.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtgpixfkvm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtuzabfapz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtryqartko.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtrtdghtfd.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtmbohzwin.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlqjvysuk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtgxwlmaez.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtiuisfphn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtlfnqxwew.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtsyegoakd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtgyczxjrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtkrhsxtzg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtzyowidem.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtxhbtdoph.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtvwxdnmfh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtkexcqjpq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnjepqbm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtrhmemtmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtrhvxbnxg.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtxuwixwsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gthtebpvop.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfqjtvzv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtggqebfhr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtlzufflue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtialacsvq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtpkeoqkwe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtsfuxsoss.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtzbyntzxs.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtgmsxvpbm.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtumudnczx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtxbjpgloq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gthpppqyap.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtrhvoikws.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtswwohbtb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gthpjedrxt.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtxvckbegy.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtvrzycpyq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtqbphpmsf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gthlpdnyjo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtpsnxpibv.html


<!-- 参考信息 -->