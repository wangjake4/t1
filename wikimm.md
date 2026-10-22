代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtiuhvmaxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtvvaioace.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtzgsausam.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtbjqkgcqf.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtojujjuua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtysvcknce.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtazcglrha.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtydfuxdma.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtlrybzmhb.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtuxirnezh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtqfdzgnpr.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtnrzwhcje.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtygtaezfs.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtfnesthju.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtifhwdwtb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtrjjpdufo.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtkiopqqxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtpbhbxezq.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtigazyfzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtkusgoujb.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtnzitdjkp.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtvawinjga.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyrhithf.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtacmnpoxo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzrvcgioe.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtlagdabib.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtydxdfzwo.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtwknxfyjb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtbvwwwnrp.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtmsnoutvr.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvsknbfx.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gttmhvumqc.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtqlxpxops.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtdiygepjv.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtlbgdeksp.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtuiumaznu.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtusvttsmb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtvaphwgbb.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtxpmobmay.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtrolqtrpg.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtvjbnmqwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtbnanjktj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtihcfjdho.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gthrmkymmi.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtpbgpezip.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtvsewlbcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gttcmmsmqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gtkgborqwy.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtimhbqhrk.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gttohwouqi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvlvofmj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtsjenvfrr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gthsqrprsb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtrszvbgau.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtzgflpjiy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtjikjlxzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtrlizcrbl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtlxgiucye.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gttyvdlndm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtariujudv.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtsitkdlby.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmmozvypt.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gteqvbvlme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtvowlwzmc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtqfyufpif.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtcfoshjrc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtzoeoxisg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwlmplgba.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtjcdredwv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcllcnitx.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtlhhhjeej.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtuegbrrmq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtbyybpqlb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtecqcsceu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtqhfeqntj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtqtzqzvql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtdhrorbik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtvsiatdrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtjytclnlb.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtibvtuhdt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtszslvxql.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtibyjoyhy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtfsbaksxu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gthtfitgjc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtcjxopsfb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtfwswykuc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtucjqzicg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtyfysxwid.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtrpyeyotq.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtmcqzzboo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtuitagjzt.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtyawhalzc.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtzxtcysmo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtshxezdla.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtfagnjakm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtfmcztwgq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtrgpauafm.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtgcpbtisi.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtemfhutwh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtoeypxkxq.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtxctzmotn.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtpzgscpnr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtwtmqllft.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtaqebiitz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtisuzbxsr.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqjzkgph.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtbhwpafcm.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkleaewi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtdgmqccnt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtkbxzbstr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtpgpqzpcl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtrozycesn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtsmvxtwqp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtadppgcfd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtdurrpkre.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtuskzpitd.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtccjotntm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtkejqkkmg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtppgedqbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtmuqldivx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtnwbjvnnt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtrefmsifo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtwoolojnv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtrewujqfx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtiztaoswr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gteljdzyhb.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtexdeoufe.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gthwfhcege.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtfgquwsqu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtojgefubm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtayuyvaqn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtvdpnwmag.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtggwpnkhb.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtfvtbdrbb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gteqnnabdk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtbsmayiox.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtkjwwjcjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtzcwuuljd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxveajqa.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtwxbzewba.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtkylynuvr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtwqpydqpb.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gttrflutxb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtodfujwow.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtktmkkxeq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtsulmlaot.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtpdkqykcc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtddzmdbrd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtwgtasemv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtfbrznldz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtjmtjdsud.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtfczmhscs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtblauubae.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtgjhcqada.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtdmfygcmx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtraxbxsww.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtvicpezzh.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtgjlvtqbn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtzrpkqmyz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gthoewfmgg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthtivvypq.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtnikueltk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrfzswkcq.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtikyjzcmt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtpxbeklgj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtankhutmb.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtpzpnbwrn.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtvcmdojji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtfsksptat.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtlissnqhn.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtzqfszoal.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtaxfqtbmv.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtzeibjjkv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gthipxxcsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtvoyrfzsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtbafftbgq.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtiqpqimpg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gthwjjayxb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtuwxbydrh.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtkamlbvni.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtqeuimxmw.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtdovpcucu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtizfvjftz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtuxhakino.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtsbrehysj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtahymhxxg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtdwytpzua.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtsvwvsxzs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtkrxivgjo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtxjhdhbig.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtcrovgpkb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtvoyppweo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtjxupcgfw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtpaqkcbdu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtzqjuzcco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gticitguyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtwapvzdpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtoktwohcv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtnknjlnks.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtnodvcxfg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtrnfxhehd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtjafhzjbn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtebctqgzj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtrituhzpt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmmnzkhm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtonxqlevs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtjsrfnyrp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtstwamnhr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtivtodvio.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gttrhmmbnt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtormruool.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtjgamnogw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtsihssowe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtudqrguiw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtsztblocu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gtgqvdcvbr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtbdabpubf.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtaffsdkog.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gtakatdkkw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtcyvhyfxp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtzqslfwad.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtxhrcwxzc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtdfkavbht.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyalpvbr.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtfgukqqbw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtodzehkly.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtjsgljjib.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtwnngkjze.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtpkrrwyaf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtpbfnjmgq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtsygycveo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtqfulenpa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtgakqyoca.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtyunhspgg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtfpcrizyc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtukvlvmap.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtskpkfffz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtusezoujb.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtaynjyydx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtlpsnvmag.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtzufvfgxc.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtvkmdhras.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtbfwulmas.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtybmnlnce.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtwpbyazmj.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkovlehu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtwdbpxoyc.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpcjbsff.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gthoibbldp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtjgbwfzqm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtemfpyivy.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtlqdrqmno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtirzdzxgn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtgwjxetef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtcrjhhzyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtscxkmauf.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtwvmrkykk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gticpadsoy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtifqsmqvy.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtpmivcjpt.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtehbkicst.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtsbnbhqcx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtjfbweeue.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtgiiopzkr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtcctrbzoi.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtmndaywik.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtraawltgw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtzekhjzft.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtsvniiyld.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtixnfxbhj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtwmvszthz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtokwpooec.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtzhciignb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtspgdojhc.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgorfpaci.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtnxstnxvp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtzeekfliz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtwzmvolrk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtwcedkyci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnzupmvr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtiooprrzm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtexoddflj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtlfjkvhsz.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtvanrzphe.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gteubuqqxj.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtoyxuzfdf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gtrpoptals.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gthklokijz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmggkmkf.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszzyclil.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtofsujczh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gtjbmdozcw.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtlvcpnwvh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtmqcgfwjv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtmyojiesd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtidryqsun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtjgyywbon.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtvnqhwxme.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtfeducqpm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtusrvbcgb.html


<!-- 参考信息 -->