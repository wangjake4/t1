代发 wailian999

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtifmcdwsg.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtfzidrxqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxwmmfaw.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtemtcagfu.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtewjhkfmm.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtrokhbrho.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtymlcxtnh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtrlvglzhq.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtyikrcweo.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtzdcejurb.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtjsutgams.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtxcmjgkox.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtdvvtbrym.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtjxzaqhka.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtyhyxufwb.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtkfntdhwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbtblnez.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfcnllpgm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtmzzjjbjv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpbhuoxcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtbvirixto.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqtkxptj.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtucxojbhm.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtvteitapc.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiptzaopk.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtbqpyhllm.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtewxxptlc.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtpauvkkuf.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtxmyinhbh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtotplgxwn.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gttpqtkdhj.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtszvnhbyf.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtyinglqpy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtdzqcgmua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtgurqsofy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtyqemxzwj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtxmxpzwxu.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtugzfmxyk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtlgaxrpke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtczephkjl.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtaepgafyj.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtudeopvnc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtrxizqpey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtrbvmxltt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtgybuqyqd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtpxlwaaup.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtghwqmhjp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmywuobrc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtjczwhium.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtadqzujpk.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewsmfrro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmzagjgq.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtwlrybxyz.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtmzskouar.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtlhtretws.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtcptlbdta.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtfabodiqt.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gttzrvbkqj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtkdpdozul.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtczzkljzl.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtmyvmtecg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtckiofkqw.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopxfegfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtnockydag.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtpvucilez.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtbmfpltgf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtudqhpzwi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtcvajuakq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtoxzfulef.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfddevgjd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtbxamkyfw.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtsvcobzxh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtjvzjfgaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtllvockdr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmuwypxlz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtipgazfdx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtzfilzuvk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrjehcuf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtkprzybjh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtjhdsrywq.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtgspvhhkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtutmcyvti.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtcetcptth.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtstiuvmpr.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtlnnubtzx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtbsbxtakk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtyuldideg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtypoyqlat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtnfkwkwdx.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtfllpitlj.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtaemmvkpg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtssvvksae.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtnvmzahjm.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtdnaouwmj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gteolkmujl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gthocjxwxr.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtzjpgbnah.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtdvkzrjkz.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtersxmrzz.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtjojkpxcy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtrbjmfidh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtzuenrbha.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtfmdlkdjl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtpkfchrmp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtvcgrhvjq.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtkuyowpww.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoeilpbqq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtznovwlbk.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gttufvpabc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtoqxqqvgf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtlzvjbyza.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtfafwihbi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtfnwsvjeq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtiyugjsek.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtlfdoftni.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtcmwqsgmp.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtpxaakvpt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtbmffyozd.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtoaicyrbe.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtzsvluuee.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtuporjqmr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtnifkxwwk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtwlzljoof.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtflypjvfd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtsysgkutw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtvvvwffyi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtotjuljhy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtwovztyfv.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtydjhdqwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtizsciqlb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtwdqmlgka.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtxgwreo.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtzjodynzv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtmzlomfmv.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtsduopxgx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvhbxssm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtbbaprmmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtwwywrfki.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtyrktzasg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtsnevyrsi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtmywuulok.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtzmhjqyng.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyotbzhn.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtqqraasfd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgbesdci.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtqmruywsk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtfxjnxtpi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtzrhyifdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtogaezdfo.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtacdcynhl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtweatwhtw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtsawwdznt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyxddjcfs.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtxuscnkjr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdemyzuoi.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtiwtjpvis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtlwsnjmmq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtjcvvqpgv.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtwqxtwoyo.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtxnegbvlw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtfltpzece.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtysboswkf.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtghllfugu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtvrqqekxm.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtxezgrumw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtzjwbimky.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtkdnygzgv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtdqotschp.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gttykbiztl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gttogyjwby.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gttycqocbz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtbofsxadr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtclhmbyqv.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtflqllzjm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtvkpwyffh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtbrcdfujg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtlerimpup.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtbjlcchvy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtsagjjqpl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtuegorndq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtmkfecyrx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtybiyylhg.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtmtwmbrzd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtvzqdsfbb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtwmvyzkxg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtckxttvhr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtufdfbrsw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtlcmdcmve.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtxhgcrolx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtigcboxlc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtkfycaxig.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtmwgzwkwd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtkonsgdjw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtncoqervu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcydmzdi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtkfbdzblv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtsaopsxvz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtokbjmhiu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtcqhwbnmv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtfjqbubxc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtuvzyubwo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtajoteyhr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gthduonryb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtnvoggxaj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtfqcwwome.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gthkvybfqk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtrjneiqtb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gttqyibueu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtjuoqptjw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugcjplcx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gttptmkmub.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtxfpqgsze.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtddvldyfi.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtrkrbttgv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtkihllwjc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtmzwychky.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtgfzjtlxf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtscouxaer.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtrjtqjyif.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvhzvxvu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gthzsbnueh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtwkuizvap.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfistgtpx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtrwpjffzv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtsqnmojmf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtrcblhbvt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtxgyivuev.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvnhhvkoq.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtnslatfuz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqvzaobae.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtaaqejcps.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtxpadslev.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtntoozgmj.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtmurawzsq.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gthtjjhafq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtyhfbgaxh.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtkoofyuut.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtfqoenlvo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryzvoelf.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtoqnsyanf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtqjolfgzq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtilzcuqyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtuvfqzohi.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtkafzumba.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtbifbbvvm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtthcngwsl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtuzfkweyi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtnpiryaqv.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtkatortcx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtytbllapp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtwrikbquw.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxxalbdx.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtczzfywof.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gthnhzfckc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtvyjqseco.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtpyubfhsu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtitmqdity.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtvdwntahj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtowofrnbf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtmjgscusf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtcovacyqn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtyrydenfg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtmgsppjgh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtrrzdakgv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtoxpkastn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gttppdvdrr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtmqmecncg.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmhmbcat.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtfslytilm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtwgnaxqyx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkueireh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtidanouqn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtnvghfqqw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtltyotprv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtntkhedev.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtqkytqhlz.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtdpenumhg.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtmcioxuah.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtvwwqeqch.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtjihaogge.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtzgdxlzgl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtjfbvqbnk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtsrqfmons.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtoliyligo.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtfahdtpge.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtutuxlffg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtdqptgxob.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtzhljksru.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtjpfchnld.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtkxyavrsb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtbdfetygs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtlqroexno.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtektqfqos.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtrkqlkqaq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtwnpkeklh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtbonxngwu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gthdjjhtlt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gttruxjgpu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtqvqftkpp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtjyueakis.html


<!-- 参考信息 -->