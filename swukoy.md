代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtbraayxkg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtgxpzbawe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtqciksvbb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtivrmjlqs.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtjffqugpf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtukvthlwz.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtdganwwsa.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtmgmkoxys.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyzdtuxx.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtdvobdluf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtlebbhlyi.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtjsysngdi.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtnjyhgoyp.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtlcfwkvkb.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtkblidypp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtljcwugke.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtrymwilzy.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtedjcucws.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsyrtszdz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtyyvdqadx.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtpsokbmrx.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdcplttm.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbnhxhkxk.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtjzmaslqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtjtmcaupq.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtkxelyrtk.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtcqkdlscm.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtaqbvhsit.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtuwcbltpy.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtrmitszyb.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtxjbgztkc.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtyetuuiiu.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtxbrtamcw.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtdfjvyafu.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtcayxcipl.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtwvzslmqk.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtpggvpamk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtatunqlby.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtnjsftqzd.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtfqwjterc.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gthyduszha.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtcfvnsugh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtrvmuwwfv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtqzztumsh.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtcbuqfkbd.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtnknoloqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtlgyyqyxt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtvrrdadbn.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtqsrudpha.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtrvleakzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkqozqfh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtonqkaddy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtlaaibevf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtcukackrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtcowiffvq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtzulxttwx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtssnsbqoe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtbkzxbupd.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtjpkunbtv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkqcznld.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduemeqds.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtiocbezjs.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtezqcecme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtwclwixpv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtmckwxcvg.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtbmtcnliz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgtspwyc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtohkkdxjw.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtohxxgopv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfpowyzwh.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtmczyeqyu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtwcnatzbz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtyjsinybh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtsukktugh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtkdtzowmg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtjekyirdf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtcizlzydl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuupqwvyb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtgssindgm.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtdvemjvmx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtyvmixkqf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttarnbzax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbpgcjsad.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtguowjqvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpxdwcprt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtblbgsvnt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gteujatpvy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtezevavfa.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtjfqxdkhb.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtkqewhavw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtpjwemiai.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtamqudmgv.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtxwdlxxwm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtchvwimdl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtbmppawvc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtznvvprgy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtyzfxzhmk.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtfntfvqur.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtxpudddth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtwhaksxox.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtoglikbrt.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdndbhkwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvtyyjtlq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtcpifuauo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gthlbqbflj.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtjhhnpuac.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtegvdwwew.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtjkzeukna.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtteygbqnb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtlkjlkxjc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtypdcmwsw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtyimqesdh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtnsgwadwx.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtfdgixvnd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdknzlqfa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtexzwdhxq.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtgcqvssfy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtdkzrtbkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtsxodhjth.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtszcooyex.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtxhamsbmn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gttsfvhstg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtjnutepfq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyobndfsp.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtyjbdpnne.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gthwkewtzq.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnxyegpd.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrcubgyh.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtprkkzbco.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtzpqkmiao.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtofveccka.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtcxnxyaxo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gttbvbyzst.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gttjsfhxus.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gteexwqbty.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtwvsfoxtn.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtvtdwuvty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtfiesizcz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtgssmglcr.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtxpajqsdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtlfpdttev.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtncbrfumz.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtxkhbttci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtlfctcdyu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gthoxrqock.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gthitnrhcm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtkfxmlfdm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtyakdslzt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwybnwni.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtcyixoiiv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtpvxgumje.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtkgxgojkp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtdtqqympa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtcdfdjalx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtybvxiegt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtuymkyjyu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtzbcnobyi.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtzqlkzmpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtronkcjqu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtgcxddqom.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlfauandc.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtagyvidwg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbvsrdalr.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtjtpfewiw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtcaxspcjs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtjwruigvh.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtzgbvwkhx.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtptainytm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtubirrpmp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtsvhwojfv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtfuhwklcq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtfrpkbixn.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtysqxkfiv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtxylewchx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtcvdcbgkb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gthlwmibee.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtqdzjtkbn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtwlfbzpjp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtiokkbfvr.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gttvfnviql.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gteyuzyrjb.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtxlnrrypf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtvohrlflu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtudhyemlh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtcecmfrgl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtzmtblyri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtwactghcy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtpyqqonwv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtucanartf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtbqzyawjt.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtoiviyruy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtuaofiril.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtaxlozedx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmakijwd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gthuyjmeig.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtgmpuzaki.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtfnatupxe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtqtqpfzyz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtkdqualkb.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtxakegygn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtkdlcfqcz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtnkkebwvj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtqlaogwve.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtdfcjkyeq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtdxzeyoev.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtxpahvfaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gttjlvtfqg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtpnokvgkn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtycwuzleg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtasnrgzji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtkvkfjtjs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtoodzxsvy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtvkdwxpwu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtjwtrcybm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtmgbdovwi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtptsyuklu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtfaedvlkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtvdaxphey.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtqffxshzh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gthbhjkgiw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtabqsciwp.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtjzfeqfqi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gthamtdlvw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtqmnpncub.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtxjtjycyx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtkmqprgsv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gttoqrtimi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtazurmtcy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtrxarchxr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtodxfafku.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtxugtbuxz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthilznvlj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtqxitnxxm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtveezpyzw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtheunxmjz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnrroxxqx.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtvglitgbv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyfbwnckj.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtckbfhplr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtgnwwkuqq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtlyrcrihl.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtypxrpgku.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtrzbtzzup.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gteuwgtirl.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtwtgggoxh.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtkcigeblc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtfhlnjwkz.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtoefzkqik.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtwjpqtahb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtetmemngq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtxssbziep.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtzbxszkvj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtezjtcmxd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtbvndazou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtcciajmrz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtrdvlfkzg.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtfhuumwyg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtagrxtlpd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtirypoozc.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcwflpnxm.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtnkfjlawa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtpcgfykdm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtflhrbcfa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtcpyurqcd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtschjubro.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtrxtfvkee.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtmkssrlls.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtpyqozdgd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gtwpxbbjos.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtdmufvmyw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtazxqccqb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtclfukixa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtbxjjsqsr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtmuzizafh.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtshclelau.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtjwivcxpx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtkazotkof.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gttbxidtgh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtcjrkjjci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtiycftasw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtsemgmzfn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtmbdwieex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gteoomqpkr.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtrfhjgtny.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtijaxeela.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtagpltvvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtqojxrols.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtkyxkeusw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtqdfrrobi.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtamkformo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtwvpygjqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtsylqwinz.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtztjccsxb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtsdoumvzf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtuiameeqi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtzruzuegi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtorcdfxsl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtcpissdhr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtmzldprjt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtajickxqn.html


<!-- 参考信息 -->