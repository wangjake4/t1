代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvkqaxbu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtvoxhmloq.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtwhsrecjl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtyddsrhaa.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gthlhjxydh.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gttherdvjd.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtxuwufcxz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshdlcoaq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtlxsalpaa.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtccwmnunw.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtmybkoqtp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorhsqtvn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtybaabony.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtzfignqgj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtlezcqqom.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtszzsnqwo.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtgyfolilw.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtzistzgst.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtmroeuaun.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztmbfdeg.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtlwgsulao.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gttkqtzuin.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtfzwhnskc.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtfjwzmprf.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtmlnlygco.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdewltyl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtmudkzwzz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtoudgsmvt.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtwpwubgav.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtsohxakfo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtwaohuwvb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlixbmol.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtomfxoafp.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtpdxhwyss.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeixfcvj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtfyvpphbb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrpwwrec.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtqhbwatkx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtpbfojccy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtlmlkllsy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtckwtywbu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtftsxblgq.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtmretfmzd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtnjixlvcw.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtpqmhfmcz.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtzcjggrrs.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtdxqwenqd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gthgqywxzl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gteyskwuor.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtltlpwhju.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtlpznneit.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcnxztleo.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtkzpucble.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjlallhtj.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtmxpfrwgk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqeqxlai.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtdfouttmd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtgemrkuau.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtfrcknagi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtvvgtcibr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtozuzgoqu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtyvmkavjx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gttnabjwmm.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtvddmypwo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtjqqfwhhu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtyezoiobw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtzuuitbqn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtyoilzfir.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtteuzowjg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtgcjuiuaq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtmwbhtrig.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtdgeliwar.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknlviqar.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtxutixfjn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtjdjyxhxj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtuxnqlmsq.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtnejitmnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtdgvwdztb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtfieolmoz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtatttjcmo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtylqymuli.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtxqmgwdvj.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtutihvcxm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtpzrfrnqd.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtsfeayatx.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtxrhczczj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtlzrgiufl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtliyxmvzo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtycpsmzqt.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrxeqwkc.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtmgxddhfl.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtgffdpoiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtcirdpbkk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtxqxkaggu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtjfgiezfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtuunlrnpr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtmbfatcqj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtnhhwsgun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtymrtfimj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtzygauqgq.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeuwnyxq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gttickswgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtdzdtbyek.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtfaysbnuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnqufcvj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtmkdgcnho.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtzjtklitx.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gthlauiffz.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtpnteowjb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtlyjzyyve.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtqlinwihx.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtkdaufupr.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtfxolkwuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtduvuaisy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtjgkdegkn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtzqnluncg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtqymgwlyi.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtuhkhgnun.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gteesrawpw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtmtboccie.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtrixcakcf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtcbahlemc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gthhloovta.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtbkyjmbyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtlmizpkma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtcnsyqykc.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtfafmawfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtlrrajxga.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gttspqkyxw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtngxajxif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtfpsvaslv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtsupwhmtf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtsutjfyze.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksnbqsgy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtcuodjsxn.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtqwnnbonl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtbmykodxz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtmbsdvfdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtgjmmscml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtvlyskoor.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gteofekhvk.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtwfnohbpc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtrqjogqgg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtqzwprjxg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtazdyeims.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtiwwlhxtb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvqaedwoy.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtdcxojvfs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtwsngifky.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtfnexdrcn.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtrnsblsfo.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtaylydfzo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gttjozsxvv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkkrnzswh.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglwsmsin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtufvmctwa.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtyhjahdvx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtrqksjtfe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtrujomtdl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtrzanmany.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtqpmjmsng.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtjfgwgtsp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtkkirofvn.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtrhxhbhsy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtpapjfndq.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtmceafrgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtmgwjwuum.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtqyesymia.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtilngwzia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gttomgaqei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtxajujekz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtsrttotut.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtzqabsipf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtghbbijfk.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtxfuhzoyl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtufjimllj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcmnpkrsg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtwfpxetsw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gttxxooxoc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gthmkmkugw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudpvjlfj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffdszwie.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gthdwyaket.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtjejrnsso.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtblgvuyud.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtzunqrflx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtbvzcddnc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtqdafmsxo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtrjngowmi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtbpvvozxo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtncljkoqd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyxcqqrb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtamssgzgi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtguekxqyk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtlegiwysa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtguzlqzra.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtoroevirk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtsdvyxsqj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtnoegpkvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtbqfprwsu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtqhltwcjg.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtjehxksli.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtuotppcxi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtnmpsvmhx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtixwjjjcp.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtxzltjoud.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtodazxatt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtctzseqda.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258.top/Article/details/gtvwzwktkl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtmddgbfsa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtnxiomlcg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtqzewjpic.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtdnnvdkwh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtjmqmddxz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtjmsfnpff.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtahpnjuuc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtcazmpybc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtucnqvopj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzypkjkc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlqfbehgv.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtkzzchpkx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaadraorh.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtbabjintl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtmwbcznok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtrlvllerf.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gteyulqyox.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtobprwefq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtckormkro.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtgamrrzmv.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtejgadxyn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtrjocjpyt.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtmogrxzno.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtrzrtnqub.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtxfxdjhkl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gthcgbrhkb.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gttyfqmhmm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtiffysire.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtibavovhe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtxqddxgeq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtxmnmurgp.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtoxvzctqv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtkvpxwrjn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhubxost.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtwhxhasop.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtmkesyawv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvwsbesu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthoegukfe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtceneyeyn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gttcnjsqgb.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtsfntdztr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtmgzhritk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtlxvmmmpa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtcdfkohgb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtfagibjxt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtqpcphtxc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtjhblijuw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtstolzlxq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gthpjfdxyo.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtatsegbtd.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzixpxmj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtlesmqowh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtwzppmrwc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtmijbamfx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtwwryguyp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtvtzcmfsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtkeiqjspb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtorftxjgi.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhmilfzh.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtqcjuvmyn.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtpfxalkiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtylfkmyhe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtlptjmymp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtnugkeasn.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtpabyhbpo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtvuvnqccs.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtykjmzpev.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtvaqbkiij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtiieucqbl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtcyzmnxwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtxirhwhru.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdyebssv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkuzxpho.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtnldnnhvl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtrcopkzox.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtrsrighls.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtuucdfpuz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtomgdnvgz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtbmjrmjdd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtgjuphqxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtbnizrtqk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtongizczk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtlvpzuefk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtjrmeonar.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtivqsohxy.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtjirurcve.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtctdesxpv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtqsofrejd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtzykmkrsm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtgwtrcbjs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtubzyoggi.html


<!-- 参考信息 -->