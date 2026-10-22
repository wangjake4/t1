代发 wailian999

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2fqstuphp.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2atqhmycw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gt2lizjkinh.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2awbxpspt.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gt2vhnqfucu.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2earpyjww.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2whtgjlql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2vrwswuer.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2kmjmhjlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2pxdowtzb.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2pmkexjcd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2hftkdfbk.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2ydhndyud.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2djdszppq.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2rappbrpm.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2qcmlhocc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2xasyztxv.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2qwywjfrd.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2uqfvbqfj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2sxzezdbl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2jqxaibvd.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2bqejhtpf.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2papjrcno.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2cbbaqquo.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2bacoesft.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfpxbdah.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2cwdkevgv.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2mahdfkln.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2abhvgadk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hpthxfgr.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2vlklcgsi.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2fzvrogeo.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gt2rjgsnhvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykzzujol.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gt2lrapvwmx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2edkyypgj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2meqxqcbz.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2wqugofzk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgtxugrv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gt2gjhvnzby.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2pgljjgpk.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gt2dmhuschc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2ctyydpqk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gt2qeggfuow.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2pnhgofee.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppvwqvrm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2qafudhon.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aodycgqm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2kltjgwts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2xrsyyzkz.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2wkkojpgq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2xqgiklhi.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gt2nguggydq.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2rvgmenmn.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxjxcwne.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2vscukwqq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2lwmnpdev.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2ryvqxoff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klijracn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ganwtftt.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gt2norgnnby.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gtjctzif.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2ghulspwg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2jaqmaicw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2frglfbpn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2xpzhqrkf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2nhwcdire.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2llagbtww.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfeuybxd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2twgaoupw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2yysrqveo.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2qjqjuioa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2wvxkdjxt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2yriwonkc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2gxljfezi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2osafsaru.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2klvcwwxt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2minpmtol.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2thzabips.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2isekynqh.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2ltbkclmn.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gt2rgotnqhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2pbvnrnvs.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2wvcmddmz.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2qptxyaza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2cdxscdnv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gt2wtvsvbse.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2uanwnyyc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysiapuoe.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcdubzxl.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhugaerj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2sayeddzl.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2rtakqopb.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2gksjfqdq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2frxcjfyy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdipplst.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2gbeprcrx.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2iaecitov.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2vizlevlf.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gt2belbjuqa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2chbtqhat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yiazjjxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2pmjqiwri.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2bncxsxai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lesgizwt.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gt2tcjgukfo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2onxprmyy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gt2euwnazpm.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gt2ihocjqmw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2jzaefadz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2nabljehm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2hoblrzmn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzyvbusv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gt2xdodjdxa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2alhicxbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2dcbecnbl.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2ntxyqgxi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2ickprksp.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2tjvrdafw.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2jtegndzm.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2dnallxyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gt2ynocvnnj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2vielewrt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjgmdsgu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2tfjojzid.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2nnraspwu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2ckxyblbz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2syqfuujs.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2zjjeweoe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2kusqoixj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gt2fbeiyikp.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2tgfhznkp.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gt2ikqfbtvf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2inpglnfu.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2jhxoqupf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gt2mckqnkqv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gt2gtesucnr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2znjyultq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2rvlzjyrg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2gkxxkvnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2uesrujfu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2odnetvme.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gt2aytcpzea.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2vxkpwbmb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxhsziyb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccyhsmsx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2vfikorra.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2dnoccrpz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2lbvqcjbk.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2crdrpudz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2blajpqtx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnngvuab.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2yttmvzjh.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gt2hpipfjbj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ggqzrkhr.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovnsvgdo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2njfyzuig.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2lxwckyjb.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2ghsdoslx.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2ouctdwqg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxpgmyna.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2vcpeikjw.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2mhnatfvi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2qnvfrsbu.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2xyaqvdhi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2znadxfjk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2etysaigi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gt2ovtzpzjw.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2hydtsgdz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2muvrvxaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2nryeyncz.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2cgeplgva.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2dllcfjvp.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2gwzeijdj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ciglhflm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzwzriqb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2fvjzlcap.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2vinjzydx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2zvagayot.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2kkzxfqnh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njjulthr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2pjfudunn.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2dqfjjvpk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2ujzbiisl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2dxmzejwi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2fqffxyuw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2tzockvjj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2ikohtwzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2naddxdln.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gt2pvbjyttz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2iaecootl.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2acicokqt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2vpqvbkbd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2nwsvjlaj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2ncxixilu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2rhcnirme.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2sapnnmwo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2lhpdfzcb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cguiifkj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2lkmxitzm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2hlwufifd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2mejshqos.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2ukwlggqa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2axzdinnc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2oqlqzqua.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2ymcshwsv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvgzrdgl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2qmqnhrmu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2fyamzuqf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2raexvlgo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2hzuqvpfk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2ivcafufx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2dduvrufs.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmcwabei.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkctzhug.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2rdlwsylw.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2nsgpypmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gt2ujbtsucf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2dvwnojzl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2fbcenflh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2dqjffysp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2hltbezwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2mxvbhxni.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssjxrggu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2ogzsnyos.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2fhaffyix.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2szoyfndp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2exilyoso.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2xfbrdbwn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iftwkikw.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2vfllrwql.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2htnaxxio.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2zzsmzfmy.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlkckgnc.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2bcdnwqot.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmvtoasi.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2gcpuvqfp.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzutmhtg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etbxgldx.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2yilpkgwu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2uabnmjuy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2crshnrvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2kmfeqces.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gt2upzshloa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2kjejbezl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2vkbefogb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2ejepzcck.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2ctpgjvuf.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2aqhvpalc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2mnpzjxnj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2wgzukdry.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndrqoqwe.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2nmhaeruc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2zzcjmfry.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2maaatekc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2nrqljkim.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gt2dmsiozut.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2wfwpmvuk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2tkbrujly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gt2piopidic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irejhfau.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2untnktvh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2qayqphtf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2cwiwxxzo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2jddylmsx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2naqcyjgr.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2yzgdvolm.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2yxtnvvze.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2meyrchmx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhoxxfdq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2luskkixs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssjoyvms.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2hxmfwihf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2rcqfvefi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2bpuufmmt.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxwfrypp.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqwmdukq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gt2agekqfhs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gt2dmxrclrs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2rlfudlos.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2jgcmjzym.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gt2sbnehlcj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2zulqgysu.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2xylvaxjm.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gt2dzayxomz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2monokhsr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2wcrnxqth.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2rwfpukeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2urxjokht.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2mfvkngdw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2sxrxmvzf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbywqndw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2yjjcddmi.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2wdnifbos.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2gvdzqlul.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2epzlqixi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2zragbiio.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2yjxgccjo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2rjuwykha.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gt2hpuvnvls.html


<!-- 参考信息 -->