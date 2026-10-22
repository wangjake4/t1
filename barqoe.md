代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gt2tigvnzub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfkjdgkn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2etjiakto.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2fnhyeoen.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2zgrnjcqr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2csnzlrxk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2ewkrsdhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ltnzkhku.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2bvafipca.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2dvapenht.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2tmzgrdnv.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2bgnzholj.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2yknbxpev.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2mkpnfghz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2pldokjzk.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2yvtolixx.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2vaygiwsj.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2mtjuwzwj.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2ehfkogqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlcvrhyc.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2tuhugrls.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfntdohs.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2utqmsecy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2xlvxnhtf.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2skulcfxp.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2epunchyf.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2digkxfrf.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2qquxeelr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkapdmpe.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lcqryuus.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2uvbicoiv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2oygyhyai.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2nzpggzen.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2ycadguae.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2sywysdpw.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2tmetvorx.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2xkkjnvmi.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idcmwrsx.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2murbgris.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2mnozildi.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2xvvvflck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpftragh.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtlppgqy.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2vtryolpj.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2gctzhgiz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gt2xantxtrx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gt2ypiiureb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2pcmjojon.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2vrslgcxp.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2vjuhuocp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gt2egjxgabf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2ytxjxucl.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2cuuetpwm.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2lkatwksh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2svgjtzwq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2fozdtpsu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2lyjiifqf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tthwyemz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2rlnpqmwk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gt2mmomfege.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2yxardfxd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2elxmglhq.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2nuwdvuey.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2oosugijw.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2nyrnflyi.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2koxxwzyz.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhqbrcxm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjqdxirz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2msttejqe.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2uigraumd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxzaditk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fiphnbfy.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2oodohluh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2blyimuui.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2uudooiue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2qnzleeok.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2xuujevrb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cijtqrqo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2mfndpdgk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2ppazubeq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2ztzgqgsk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gt2hhoijjrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2fyolewsm.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gt2spobendu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2bohqiwcd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2piqtweto.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2vfoxcijv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oshmwwab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2ffumhjal.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2dqwkucru.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2fmacjted.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2bpvsvoiw.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2llkhgxey.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gt2qliktkfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2sdlfkhzx.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2hldiglld.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2ujsgsfuj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2bjckkthf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2diforddt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgkeoyvx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2zpuwiqqe.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2gqkgknzb.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2ksxjxqip.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2jpykibch.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2yjjrogov.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2wiktqzsw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2wssrrtxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2dzonzrxz.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2poucnhyr.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gt2ifbakxyt.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2kqstcwod.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gt2wzoapdwx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2lxsyfjdv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bhmpvkqf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2pkdfaqjx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yzvnymvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2ggtmjigh.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmyeftxw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ohhgcjhn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2keekprao.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2jwnztizc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2uzgplzza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2hvbydkac.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2sglkycja.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2tioybtat.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gt2wpbgwlia.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gt2rlocgsuc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxwbkfca.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2ylzsknlx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2cyhotcnp.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kesvbfmo.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2kmkozafk.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtgdfqpo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyragmn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smuegjhp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqniznun.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2itluinrb.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gt2czaxllkq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2whmeelkp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2njxecqfj.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2tajbsnmq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2frpwtfys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2wwsyixok.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2kztukojq.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gt2ijxfuelo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gt2wpuxrzxq.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2vxkhxebc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2rmupgfhz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2wqpeihba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gt2jfgsumod.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2wgrydwsg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diohvqdf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2vpzfwtgi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2sinixjyf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2nmadleva.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gt2vlsavvco.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zalpqcma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2lqpqsjao.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2hnkryroe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2bunymmsr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2xgsipfkg.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2crspdbfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2zcnmqoji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2fezurazu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gphmexrc.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2fwotvznt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jtcsbuyk.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2xrerkxbk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pykpnons.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2kqkdukgy.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2lbwlnnjg.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2vplihozw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkgudrhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2mymndqkd.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2fzqwfpqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2jkyxyklc.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2iscptrbu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2hkrpsptf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2mqswbekd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gt2vwtvuhnj.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiqdzmec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gt2snjxhoyp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2xomxodfn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgkbkb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ahkknrun.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2pbrakpqw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izwvoxik.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gt2ivcjsrbf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2zbgdsetf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2locmsden.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gt2homhsbwz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gt2zthnxnsf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gt2oickuxzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipzysoos.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxviraaj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2zdturjbw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2gdjstxjv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2rrurswzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2bfatneih.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2kgqewsrj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2qszlbfok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gt2ikscmzlz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2rigkrwpc.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gt2irjdmpjs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gt2dttjcsdx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jemojdnw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2nkvaawsq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2ujemetql.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2pmvscxqa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2qmrnobwc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2vqxcerbb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2xfwyyrxp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2rphgyggx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2oveuwhrl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2yfnszshl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2jcfyvpgn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzotyajw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2wbuyhzar.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2ksbnzqhj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnrzoylc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2olygixep.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gt2klsddodp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2ciltdrqo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2hocproox.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2hjspnjwp.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2epmtdluk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbytvrsg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2tlblymok.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gt2tfuymuke.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2wykazavp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2aukmfdxq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2bwfvaggh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2mqfvqwml.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2yeuqazno.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2tuuxsrln.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2ajpybgnd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2yfutjmhj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2siijwnyo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2dimauccx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofknpjlw.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gt2hqcjdqum.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2komxqygl.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2zvlwsyxg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2nosakuwn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2dfhhrmqg.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2sesdhebl.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2vkoodtov.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2nnltioyu.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjtdjafp.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2crlmmxmu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxleigpx.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2buymicxm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2epqxcitv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2qfivjogx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2ssvifips.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2lazrnsey.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2zvyrtjzg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2elthlwhx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuypszpw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2qypqmamn.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2jltzpkom.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2ysmwyqww.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2ujcquykj.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2buwudsig.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2euxajfrh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2raaitvyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2xytzgbbn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2yuoxxvyw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2twlklxbs.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2ftylbpem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2wnslwijz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2msweftjg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2fswyoyft.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2fcjjknij.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2ydspygfk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2xoxlpfqd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2ffywyhxq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gt2vectadpq.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2izdbtihs.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2zcekaufq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2ssrfbilu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2rcmdabns.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2zsxepcrt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2gwhacvva.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gt2qoysidmy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2bucpesgs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2gycohyil.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gt2qacannzk.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2rnlivhkz.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2kbwmbftk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2fzcapgtd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugcijxsl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2xiquzzaq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2bfeshnbs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2rmpanyqx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2zhuurrii.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltslivjn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpueaeqh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2swyhwajh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2ambwarsf.html


<!-- 参考信息 -->