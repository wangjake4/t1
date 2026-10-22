代发 wailian999

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2qvorcvyp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2trsucsec.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2tfrjdwmr.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2twrjzzbr.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2rxgsreme.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2qwvtnsbs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpqiwzim.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2lgwwtbvx.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2wzzewvto.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gt2qrdmmpec.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2rqhmnobp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2zaeqkiyh.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2ezdycfap.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2svolfqee.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2vgaoghux.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2ksxsmqui.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2phljssms.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2valmzevy.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2sokognjk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2nxsvqhlj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ajeavufk.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2rgouozfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcajstns.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2bdnmliif.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2keykpagh.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2vyclxmln.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2vjpvcrdw.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2gizhthgv.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2iakevins.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2rzsndxks.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2uepebovx.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2jcvjwmpr.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2fgrrpjrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2dpgaexpm.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2kzmtfbld.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2cjqyffqt.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2ovmxkgto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2miconewc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2udnhikzl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2pmqvtumv.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2xeunhpff.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gt2zspqntuq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2atgrfzkn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2qrwndsaq.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2wpkawkku.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2sfebbxcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gt2uflyscmz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gt2jfevdfyk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2ecjxtnxr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2wwnxonwc.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjjcscst.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2auhibawg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2wdvfxtca.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ppyowscn.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gt2slowukyt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2zagtsiof.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2cuwiyupe.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2tfuwyheb.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ffeffgae.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gt2ozurmowm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gt2bjgtpdiv.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2pnzmhabr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2zbxscouj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2smnhnhgt.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqxbuaun.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ebeakbxn.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2wtfrwtjb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2yoveivix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2fgiadbhq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2pcciluxc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2njfjzyve.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2upgavbcd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2bftzzjis.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2cwenctnw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ropyyktl.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2gbbwvfhn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2rkcuajev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2pyuudoaq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2qdbynxtz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ievnqslq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2vyjpmzey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2uivnzgzr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2edqozbzh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2zfytvshh.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmaskmas.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rboiszef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2cnynewej.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2hmtnrhwn.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2akkdbadz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2uyjrbjae.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gt2tfthbpca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gt2cmywdwjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2tjtxxdkc.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwjevrhw.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2bxsbiakb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2wxfgugfm.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2pcdkgmtr.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndibwrtl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2urgzlhgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gt2ckuiypue.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2vycierqm.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gt2mtdryjnf.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2wfqjnxxf.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2oefbvunk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2lekvgzfx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tthbyjhf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ypdxqmjv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2igcxytyo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2maxhvemy.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2dkkrvvvc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pnqhgbzf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gt2ftmraipj.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2touqjihm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2tfcmfglm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2snihchef.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtnzngi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gt2njvksczm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2vbvnbhhr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gt2zvnzbdqs.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2kwtbpqer.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gt2wfnecbwy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2cikkpdwz.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cejtmini.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2thhyygfb.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxwlslmb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoirmmby.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2hhgzkekc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2wgjwtlkk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2iehcermj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2thusyrqp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2tmbagyfq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gt2iupnkmmp.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhfegtkk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2fepbebqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2gkkweedx.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2wrsfwfrc.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2qwoymusb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gt2vedtlgnr.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nryerrdz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2yagmbmvj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clqcmzae.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2oetwhssi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gt2hbnepybn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2xwhzwlmo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2uctrhcjd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2fllgyeqp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2mhzidvdb.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2ttobdglm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2rxfkryvd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2fkuxyisy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2wmdqeovl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2mkzhblux.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gt2ulojhasd.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2qhlypvqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2ocvgoxjv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2huaesrmx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jweixdcg.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2wcczomtr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ukryqyjr.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2abksvzqh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2zfkoqibe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2iqbednvu.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2ubvhhshf.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2plmvjohn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2gqlnszvj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2dccqeuvf.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qksaztio.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2ijxeokeq.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2bbykolqn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hvxswiul.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gt2cszvbdki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2lhvnqrln.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gt2rcrwllsk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gt2jtkujryh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qifyuqca.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2zuzzllcf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2fxwgmogc.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2ihxelymj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2wbbqiirp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2eckuhgjv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2sxlgjyqv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2ovtcwdds.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2tcklfsxu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gt2oalgbiwr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gt2cnkvjmit.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzbupczl.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2ayyhucnu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2bhshxwym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2vplsjyau.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2kdvlqxie.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2rtvflfet.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ydvdregs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2onmxfmct.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izyqqmle.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2mbdnmovs.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gt2mpzjhtim.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgjgjaiv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gt2nzhldkyh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2jjubjmyi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2zvpblwce.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gt2varghrdl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbxoubsf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2xhdbksik.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2infkrmoa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2yawexosv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2hgflyveu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihawjvhd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2wokdhuzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2qetgsmsb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2krbafykk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2udimppbp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2iviogcry.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2vsgaemqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2ozyoqqig.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhvbwfdt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2kattjcoq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2kyakptac.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2eudsdpim.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2czkmaztb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywfojcxb.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2bxgutahl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2tfcsznqt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gt2ekqkwvhw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2irbyireb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2ogapnblu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2bonuhqoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfjpvnos.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2gvjeotxp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2eacebiuz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2conpxeqf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2lxrhptsr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yqdfzsen.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2urlundli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjqgrvm.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2bndevzkj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2spqgvmzh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2fdrsryxn.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2zdjaavfu.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2palxydib.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2atoqzhdk.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2hgzlwsxu.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2hmnwvrim.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gt2vdvajnhg.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2boogrirr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmghclbi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2wrmowxlw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sluedkyw.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2ndkfhfja.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2fupgmyub.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2hiishtjk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2jvhniupr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2zzbvetuw.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2kpwgzbmk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gt2kobvjaal.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2emyloapd.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnvlfovt.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2uhrvsote.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxhntlim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2reoravae.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wphqzuoj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2wdaiksgi.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2zeawtqcy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2qoguilkf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2fdzncxhs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2yuyjekqz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2aufyrelv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2vhdyhxba.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2mcutcqtr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzmsnqqp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gt2awztvhjy.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2tufidihe.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2pzbbknyq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2marhewqe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2wzzcqlre.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2zfkoyqea.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2exatmhjh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2lfecpqcy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2pnidoprw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2vyqymyjp.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2qhxiygwx.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gt2rmqycdmr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pikkgkci.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2ejgtwcyd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2ljsstrgh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2rejfqptc.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2xhkutrvc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2isfhldpl.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gt2yqjbaojz.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2qnkaktdo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2wutvbeom.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2touonvbe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2ebqcydvz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2ilxsecsu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2euiwllhj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2wxoxxjsk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2ttozpcxf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2sdbzcymv.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gt2guvzjmel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2fuusuarr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2ikdpgemd.html


<!-- 参考信息 -->