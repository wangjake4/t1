代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2woigtvik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2rgvoqpwr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2hyphjywx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2uvgpgqtn.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2odglwpwx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2rkxesfvj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2xrazzyfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpwrjhzh.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2qscsqvzx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2kesalcep.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2ployopvd.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2qwrqusnz.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2oldwaunq.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2ukyopozo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2ptorotdt.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2ejbfxywo.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2usyaaebj.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2sbrkvifn.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2ipukdyjr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2ynysgkjn.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmaxxkfs.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2zsjjpubz.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2iveoqswp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2sdoxnryi.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2smvpdzgd.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2cslcgxls.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2nvdjferr.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2kjjguwob.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2wbvpdmvi.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpqbmonw.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2yepijdpd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gtemkhsk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2crcrqfcl.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2leinrnhc.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2irylklri.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gt2emovgfjk.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2iqkkaxpn.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2dmakxtrn.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2dnbdwxjw.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2micdahzl.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2scogreyh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2efvinrfg.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2etxrhvxv.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gt2oejcrypi.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2yfofybvr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gt2dswnotix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2lteatvif.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2abgjpnua.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2xrsndzpb.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubkjujod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryslefvc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2sugdiepe.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2otwzxhry.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2lcgeizjk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2rcsnpokf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2fqhizgdd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2yjzhxnlf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2xtwmnmhc.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2eeyiiczl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gt2caltuotc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2otryickp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2brbnqhse.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gt2trturavl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2phxplhox.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gt2nyhugynt.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vimdtxxu.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2hyaynqly.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2gtqhpcgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2dijyqnro.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2nhpiizqh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2flhrshyl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jipbullw.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2fyuhcfrt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2djwvppyd.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gt2peotjmdz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2exiojzrx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2sdtrftwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2kmcuvzfd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2qhzwpzxh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2wnevmpps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2umznbfkn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2ztfdrbad.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2kaixklzw.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2xquexcpf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nceoscyg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2qxhaqmpb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2tjptcauf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2owjeubcu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2ltxxlmvl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gt2kfgojqco.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2qddubdji.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2idtpyloj.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2vwwwjhaf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pirelibc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2kbcmkkjp.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2impwerym.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2vledeaax.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2dljdazri.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gt2egwwdrss.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gt2bpfkrsyb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjiwimbh.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2nirzgyby.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2fnyjcjbg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2canaybmo.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2lcxitjnq.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2zmeaaukq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2zasqotwg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2xcajnzhy.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gt2vxswnqnu.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2mpporldi.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gt2sesomigj.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gt2hzkrbrvv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2jlvblbkb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rzfxvscp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2rjpdgzgc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2boorfskg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gt2rbdeqbul.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2piqfbgef.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2xadxwmbe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2vytwwvgu.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gt2trluwlgb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2uttorsbv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2pvivxhes.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2cuaxgfoj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gt2btzqivyg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2bxkubmrx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2kltpnqaq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2niblgevn.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2haqbphjh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gt2bzyzgcit.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2qglbsvjh.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2bgteqhfj.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2qheyhzzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2qmpcrbqf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2hypcsrtr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2idprkdcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvyjsiaq.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2yllhvsed.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gt2mxiiujbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gt2phprqatf.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2oybwkpxg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2zyezfvki.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gt2ejyeawth.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gt2isffxdle.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2taqokszg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2sxsnwsiy.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2jtgtcqmy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2fiayvisk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2tinaxfkq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uishbdcd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2fgiushtn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2jpimtpwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjvagpvd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udposocn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gt2swubppvl.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2hoywccbd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2cmaqjivi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2usizchte.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2wdypbuvc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2ntgkdufh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2relaowxa.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2ffzxdwyv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2furoxrrs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2qhxxyzzl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hhoklewd.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkimrzqi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kufpfogt.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2hwzfugrm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2fvdpcvcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2mxowkxpl.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2ygwviyxf.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2nvryytou.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gt2mdqirryv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnjonokn.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2bjohllcu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2dtioaerz.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2cawodqiu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2yoqqxouq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2seoysloj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2dualgexe.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gt2iluemhdb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2ptvueofk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2vlbmiqca.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2zmszryhu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2qprtwkxo.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbxdnlzx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hffctoze.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2bomljfan.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2mepxyhwc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2foahispg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2hvawpvfs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2shjfjpic.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gt2mmrygfeh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2zayfatel.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2ficknuvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcbfejmw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2riupfcvf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2mvmulnin.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2lbdakqjq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2tnqppbaq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2lblyhosa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2lubawuuj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2chtpikfm.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2lwmxrcmj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gt2dtgprtfr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2lppxynoe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfuequiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2lcyswgoj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2xwtwoeaz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2kyehnqvs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlzcewcx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2ugdtzgmc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2owgfwkew.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2dwxgcpzc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2brfjkzuy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2xcpibfcc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2qouvqfqv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2euuahtuh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2cswmgedp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2khczacln.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2crtbxbvj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2fgiyxtod.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2bvsgpvom.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2nzcksymf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2vykibdvw.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2sunvvdna.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2wcoxgrzq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2wvfogxav.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2uqhvxupf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gt2mcewtcag.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2mvusogwi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gt2qvghobon.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2nfsciukc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2qupvdezf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2jycinxlp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2ojunwxcj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2qplvqlet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2rlfopfru.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2fpgvxuho.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2hjjnelwf.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2scrkvmvt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rflxtbte.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2itzakgdk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2jupkldvm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2itnsinqn.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2avtuknic.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2ppoteloj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2aqlvdfek.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2mossoyzy.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2njpufdgw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2ftmmgzxd.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2nwsrmunj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2kqumrnyt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nylgsupt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2ycfkwkwj.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtwuhcoj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2nriqzcrr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2xuipipxq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvzxpxam.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2bdlqtswh.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2zkreynsz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2kzitkfop.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2rgzxtimf.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2axukxgxh.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2dmzrmnfj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2mhaasvni.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yltunepb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2kpegumib.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2wrrwslaw.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2fvwdovoo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2hzhhmnzc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2jzwzkwlw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jygqtbdq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2eqeawfur.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jprpnnuv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2uazvnlqr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2lmyafdnt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2pizvxlta.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2qbfrxbmg.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2amgisxmc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2dwxoutvz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2xkeosizz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttjeghqm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2pcdwyzut.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gt2vraboviy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2xdputxjr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2exoalrby.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2xjebpbjk.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2lypjjeoi.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gt2omquosrd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gt2khjncuzt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gt2yianemsx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gt2hitwmzkz.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouiakgbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2grtpwpty.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2vuarqaxj.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2zwouiecj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjqfghtx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gt2mqhqzdlp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrqflioo.html


<!-- 参考信息 -->