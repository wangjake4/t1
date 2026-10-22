代发 wailian999

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gt2hdwbemkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2wxypvcqq.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2qnwzkgni.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzfkkqjk.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2oyipkvjo.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2khucvvqb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2cgrgdoag.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2sftbgglf.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2jhgksrfj.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2wrelwpld.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2urishhox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2muizsyje.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyoyjxwa.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2uishkwdu.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2gzpxhfnb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2jjthzuyf.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2awpwtmkt.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2lcheihaj.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2aiwatrkx.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2vfecfsjr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rspoeeac.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ybedivuw.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2knbrjsou.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exmphrma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2nxdzirbk.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2dtumktao.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2ibanglfc.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2nyxvqwsh.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2sunyykxd.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2tdtrneyk.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2egqsthde.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2ynxfrmur.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2khddlxgi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2dcadvbeh.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gt2czatnyek.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gt2zstqlyke.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gt2yjonowlb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2hvovgnwq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2hadwufmc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2nquozshh.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2hiibdjru.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gt2kiatvvbz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2semccisu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gt2ymvnywtp.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2ymygbuqx.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gt2xtirythn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2bqvtatrz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vufqqrie.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2rwqzhcvr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2gizmukrw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2hcsqjvtb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2uhmdjizg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2rfuwsmjj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2xshdcjoh.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2yktnbrml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2aqbwglcf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vviagprg.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2rockeebx.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2wbtgofoy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2lekusxry.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2frecnnik.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2bbumjfsu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2lgorllcc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vwbglvrj.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2uunoaiku.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2sarzncva.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2ejkawfyd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2lhzxwwtu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2xvkqajkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2ggpemxgp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2yyrifohv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfbuzkum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2tmktenxm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2dpocsncm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kbbbqggx.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gt2urqmhibf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2mjugewgd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2mqsqvfum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipdojoyp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngvnlqdg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2jsqfdpnk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2girctpgc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2bcplvdxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2pwgdzfnw.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gt2slkwdbnp.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvdypwdx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsgzmjxy.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2ctuprfyt.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2nmebiscg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2rintvndh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iijotubt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2vwvnumur.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2rxaisuee.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2nvfjuenk.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnboqrlk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuapqdbe.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jokwjknl.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ttmiypgz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2caqdjhnn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2vmzfxrbt.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdhvxpxo.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2izbjsitj.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gt2xwwdvprr.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2cmiszees.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftrvtdsa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2hwbrmxva.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2wdyziqrz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mahpyacs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gt2fmlohytc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2yefupqzl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtbfbzji.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2ozokpqld.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2dpujtdet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2xypqqttq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2svmwzxsb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2cwvefebt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gt2tunqlamq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gt2gxqskgqf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2etyxdajo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2sdtzsolo.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dccjmbqt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gt2ofjbwmlh.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2mwxrwbhy.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2akrvqybu.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2iovpbgut.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gt2gjsnmnsm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gt2vplyypse.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2gfqqmezw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvmhezlk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjkwgxs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2qigrgzvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2tpxiwchb.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2tuyuohyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2rvubiutl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2vvysbzdw.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2tdduhvzp.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gt2cswmagoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2gycyulcd.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gt2vqvfsmal.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2ujprkizv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gt2osobaber.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2zwbnapro.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2lmmzdzjx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2zbcuwdxh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2vjdvahuh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqhxfixx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2hjajqjua.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2bdqaaqwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2fseiioch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2wwjikymq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2kopegqys.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2nwrqluwu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2leohlcvj.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gt2kurfqedd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gt2jvxbrpmi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2nklioyyl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2oeowvmdc.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2yogqilyk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamjyasz.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2snihlivv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2jfanxjnd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2eygdshrv.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2jcerjrhe.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2aabzafkp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2udtsbanx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2qrchxpfi.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2htuqwbsc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2napaxhbl.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2qsfzrzcx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2xctgldgk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2jqkgbkyd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2rusuuoak.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gt2oxxcfraf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqhhprqa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2xzbsfhae.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2pztieqrj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2hdyunrzj.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2eddcmjig.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2negdynmp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2roiityuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2fwhrkmnb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybvnconz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2hdorcyfn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gt2pvnwkqgl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gt2axseksev.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgrucnso.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2ieihtvdn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gt2zlshazcn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2hlaqlbap.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2sxdkhkmb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2uostaaiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2fzkclhts.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gt2htptwrdx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2oymvfhli.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2oatynuau.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2gadsqgsw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2cbuisaqw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2xlmdmgqr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2tjnilmdz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2dlxjqzzm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2yehfqdby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2loasqjxq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2nujhacfy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2sojkbltg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2hghicdyh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2isfauftb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2eleriypf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2nakcpaux.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwcnzyam.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2iasrqaqw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2kcihosdt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2hymfxzrc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2yiefoqov.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2jjogynys.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxooxfyf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrucdrwi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2jafwjrhz.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2pwtjqyxq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krpkhczo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gt2ltdnadux.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2higtutip.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2sjhmkbxw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2cfnzfirt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2ojosgxob.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2puekaelm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqjgsndb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2scrftwbj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2hrdifjcq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2qqismhdb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gt2rulqqzjs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcofllqw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oopxbkay.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2kcavkdem.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fhlnqlzy.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2nnvdtmvr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gt2booeekjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2tlpekmey.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2zfecdzsm.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2dboqgawh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2gpxwmfoh.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2gdxfzpoc.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2xfvaajne.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2uuybwnme.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2swtlmfcd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrvfnaq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2outmetpo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snxsqjwt.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2pfzsvjvg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpvxevar.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2avknzast.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2qeymehzh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2yiqaknzf.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmlwcdgx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2rlgcvqmm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2iwgyysqc.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2gdfrldag.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2zxyqjxdi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2uswcjmvw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2maqubtxt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2yqdhemfn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2xpvzhnus.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2bmjyaqca.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ajzcdyjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2wbhvbdcr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2udgzkfry.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gt2eqpnpgjr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2zyoubsyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2zcobrrqe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2jbcgtkmx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2egqarliu.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gt2ibeuxoef.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2elhfxubl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2npbmtomp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufbkqfen.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2zoqeleyv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcbyhwz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2dvusskxx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2hqheldow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2swmfbvnr.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2vefgofiu.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gt2lyphgoae.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2mxzzlruu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2mgmpeduc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2vmfmrehq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gt2psbycdtp.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2wfuyeizk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gt2zmnsmhbw.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2axlcjumc.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2hxmsfkam.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2rxbelsoc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmcmhkke.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2nsxjscho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2edrvbjmp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdqgeovc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyujmusy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gucivfjj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2teznhhkz.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2ngkarklc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlpehmqw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2mfnvclzi.html


<!-- 参考信息 -->