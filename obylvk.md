代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtxgshffes.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtuvrdbbsi.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtaydqrlvu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtvndlajxu.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtqpijhxxu.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtuzrvussq.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwdksqrlu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtdvymujbx.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtkgesxadu.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtwuleipxa.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtglmxeigk.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtrdvxqtro.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtauqjavvy.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqlxzdsy.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtkmitkpff.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtulnaxdli.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtbthwsaay.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtwqyjjiyq.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtphhslzos.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtgubohksz.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtxqsmnsqa.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtfqdzkuyv.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gteurlgzud.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtbdcpjdua.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtuiiwnmvl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtjisjovdx.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtzvwoafbn.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtsizejjow.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtmotadlmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtdefgwvsn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtrznxxwpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtngeyfnqv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtobwdxtrc.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcbemyftk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtcmhaabxj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtorffpysr.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtuozganhk.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtmgpomjjt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtizxoawrr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtdamebvyh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtygwzhpel.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtibxnvakc.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtfncwwcno.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtxzamdgjm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtiqudavsm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtkwelybzz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gtplgosysk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gttkfrxifo.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtlpjqzmve.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtimknwpik.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtwuijuwun.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtbuzfglwp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtswcspkcd.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtnnkwbytn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gteuiwxagd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdxmknbpu.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtvbgblddh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqalccbjo.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gthlxktqhm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtvlugwlph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtjzagffcg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtlqcsmdmu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtzwtvhtqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gthsrghkjy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gtmhujqypq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtdiganjpg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtznzpidpn.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtbpmukyjn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtmbnfiacs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtwrngxlki.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtshaugefm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtxyaotlyx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxllehawk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtmomyidiy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtzetdhgzw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsapiokf.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtkaeuxwav.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtktmplyto.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtskcdqefs.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtxwwgkvnv.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjtiaigvi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtbiydtbve.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtbwgieicy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtkmqbbjfc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtwbocxrit.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtpqvuqpbm.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtaxxblkxx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvqwuouby.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtnvuyzzou.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtvdhgqvau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtctjvbgtx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtnhpahalg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtyhroybli.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtjbrkcakz.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtdycafqwc.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtrrcdaoyk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtufkimpww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtevfauexp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtaljoikvy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtrkksbilc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtfengpylj.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtaoozwqms.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtsqpxvmik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmprhvqqn.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtzwqtdtma.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilkkcgrf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtjmecphuw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtcyeqfnlh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtkuqlsdqe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtpnmvztyz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtzgyqzuhw.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gteughlzip.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtkeyjcpoy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtthptfuoq.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtfcsbjypu.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtwjceheka.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovsihurr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtivckeezx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtegmidxfw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvopqxuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtnaeoaunw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtehxntxzs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gttjswvsqi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtitwpqzqo.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtreebhycf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtogbdoxhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtspcsopve.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtivsnelbr.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtawnnzbph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgcdpcve.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtyngmwrxy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtnbqimwmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtidwtkvwo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtxdigunkg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtvonwunol.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gthraelfli.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gteokgtdfi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtzckwclwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtlgrmfapf.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtlokjbhca.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtjvbmyvks.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtuqdfacrz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtkijwcxqt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtkckazckl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtgmkijhja.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtqqdvsxqq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtgyaqisoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtwhxbabkd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjouceuhk.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtzqviswoz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttstgprnx.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtqvvpeabx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtxtalnosp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtgzwnmhkk.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtemjybmcj.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtnarzqfvf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtahbbkqkk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtapgykciw.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbojpvkwt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtbukgfytc.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtjyrcvgtp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtqwzjqzar.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gttbyylfpq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtmhnuwzso.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtzxiaktwt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtuobmlqon.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gttslghbdk.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtnksrelcf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtmwjowaik.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtunscittq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtexegcohz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtndkhapmg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtnbfsvmix.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtyaglpnas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtllpzpckl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgexzhqnr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtbttifibx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtrldwqwbi.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gthdqxfnfe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtyxhbzebd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtplbllegi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtjhumqjxf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gthdjrgozv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtesrbohlq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtlebuylfd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtitwpekdh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwetdvicn.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtrzblxdcl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtjgiephxw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtydcuspgf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtopdggqcj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtmubntrah.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtkljeprnv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtlcnqnwfp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtdsptztzz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gthhmaujjj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtxjijmoos.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtkiqzovbi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtrnqlofre.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtoegmuqlo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtccvrzuqh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtbyexfiui.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtednhbihn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtdqearvdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtvplvlzpm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtdknkyqxe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtrrtjrymm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gterruhzly.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtabhbqiiy.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtrksbpmxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtrsjgggnf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtpxhfbbso.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtcxhjdubv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtyyfbeour.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtkhuxbwrl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtphlppixw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gthrnarbsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtjnmawcbd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtfpfwuzzw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtqqhnvuto.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtwlbfaeha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjepesln.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtkzdfbcxb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsoiebnjc.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtntwrbfwe.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtoptabtct.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtovwjozpl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtafrfwznm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtxberobgw.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtncchjghn.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtxwdhhqde.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtecuafudg.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtspnzmxxn.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtmgkwwoyq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtxlazskol.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtyvizpcgv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtrbdhcmif.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtrypxvkmb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtbxtaxhzd.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtojneqldm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtrhejtzth.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtxpigeafr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtlbrhzrmo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtieysqurr.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgwytvrqy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtbjzjqkqn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gtavphnhas.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthglrbtoi.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwydvksew.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtjxumdsoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtphqgzssy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtpuwysqyj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gthpknuvdv.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtylvtykhp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtjfujsqxc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtytjjrhpo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtsxzjpygc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtoosaboyj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtlifgpvpd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtfczrhniw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtxfgavfwx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtcdbrmkpw.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtptbpgask.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtmuwxfnaf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtexslgoum.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtzxaegnfy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtjadxuelc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtauuctsyx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtcffjzyfm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtgjmltwyw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtvvckvvfc.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtplgiswho.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gthteavjdt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaoweadl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtkjjrrwat.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtjavsfvax.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtftgydrnj.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtmmnvoqyy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyuxdzmz.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtghwkuwlo.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtxsokrltt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtnkhmvhbt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtaxrwazbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtonnheqgl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gttiqichgm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtqrocwocs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtofogultq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtzomylzuj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtbabeatdl.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtxfolaytj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtgjlrckto.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtauezgpmm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtogkkkdqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtahmhtydb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtcomrkcyc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtjljfwbtr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtamnfkpui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gttlohqfpg.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdphgjes.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gtgrkawygn.html


<!-- 参考信息 -->