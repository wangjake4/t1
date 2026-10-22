代发 wailian999

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2anpsbnsw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2vwnpzdop.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2votvcqkr.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2yyfgnbtt.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2ikpgxuhq.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2inwpwsig.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gt2lpkjhbim.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2nfelvpja.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gt2gdhxdsij.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2jhsshwgh.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2heiiykdf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2aelbswia.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2dsppibcx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2qlmuvbsg.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jdeaqtrk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2wppigztc.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2ypdsjhyg.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2vhmcqjiy.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2krkkknst.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2qgsbuqpb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zjraohmc.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2wbrhkolv.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2klcjgvvr.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxwqdcky.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbskwsum.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2vjapwwui.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2uebkoscn.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2hbimlbgl.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2psyjldxk.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2izkvzqtb.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2sqnavyex.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2wuzxolwc.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfjjtkis.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfyljpud.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2sjqsfwcd.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bktotsgb.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpcyncsf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2ltklgzyx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsdbtlrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2dtvmbool.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmlsuwq.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gt2kcmzuyre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2fpspmgyl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2jihtdkur.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2hzbqsgty.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2bdyqowtx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gt2qjqfznor.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2esfliqvb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2ywfrtuox.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2czjonytr.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibmhqawv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gt2qlipjamn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gt2fgxqyqkv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2lilzzasl.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdjcuzzg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2khkktuqz.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gt2uibfxsfc.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odctfbqd.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2fktzqwxl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2poydovdp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2soudspvi.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2lhlqqxce.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkeijcvu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2aaobdlbk.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2onpxhbxw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kbialege.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2wkiwoixk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gt2eopnozdk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bzhrbhns.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2decsgvwe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2sjqxubzy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2mzcupedq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2qmnawbnc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2knfxedxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gt2flxhrgyg.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcbgypqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2eqhlsuqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxcnannt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2jpczuzvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2elowhpul.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2avlsurut.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbhpaena.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gt2wyelecpc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2cznnwqsw.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2twibpyio.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwbdogqu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2cxaweebr.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2xqikyrcm.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2mtfpumum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2ycnfgpcr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2bnbikcqe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2udonyuaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kruiyfxs.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2etcbzsug.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2goynefcy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2tuuopgtq.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ivdewmgw.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuyqvsoa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2dlcaurww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxjtxizm.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2oerkywlv.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ijbstoqt.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2ouxrafea.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gt2wfxtyvag.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2ldjhvjap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2onoirfrn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2tuntipdv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gt2kecnpfil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2ckzcueyo.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2pzjcsswx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hvypvbpd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2mpadipli.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpmxrjtk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2pkyngcyz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2ynldpvhc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2fjcslnqd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2cmfbpdzq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2syeyhjrl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2kcbrfavt.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2yhhurlvs.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2dxeothzp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywqytzbc.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2dgpsrnwn.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axknmgfe.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2lqsvcvip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfmhiutr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gt2kgcwwmfd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2jngsrtac.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2gtrmvsht.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2skotijth.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqeazymb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gt2dpxyyrys.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gt2jntfyhna.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2adkxwarp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2wbdrkfvc.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2tfhbvoqx.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2bawqkoxt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2rlsoancq.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2ixkrcouv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2trkecgua.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2qzoyixwi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2uxtvumzu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2cvpjmort.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gt2wuxgkkqu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gt2rzmklsfc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2honlvdmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gt2mxvpgtgl.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2lpgmgnlt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2dkzxriwy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gt2yldmyrvx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2qzrrmnhz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2zsjfabex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2zhfdkpio.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2xcpkqtal.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmzpghtv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvwmwgic.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wtgowziz.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2wvztuzdw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ckunvguv.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2fsbgcabt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2dvfnvlvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2tkkgvpzi.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xothzgtj.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2oqmommdv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avozxgbr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2sfxejypp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2fpehoewx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2cwoyhbeh.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2djoahzsb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2armfaydm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amjpcqvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2zovfxxrj.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2itwrljfs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2qmxwncpc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2gkvnuqpp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2evbghghu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vjyhsyvj.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpynucnn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2funvopxq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2atjezxob.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2apodqqft.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2bsbwjcuc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2dnkpwqsv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2dafqzojw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2fmelcixr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2kznjunir.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2vrdvlcfr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnxyoyqx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggimwfdy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2jjmeewuy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2xkzdljzt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2qzkcluhp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gt2jebkvedw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjfvbuna.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2tzxpitnm.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2axjkbhxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gt2awtkvqxr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2cjscibpr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2szgxbqxq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2azyaemmr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2tkyzaqzv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2wuemxxhe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwkbezmt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2ccyvkolw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gt2xkvnwxke.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2jgbtxqtk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2hrgaltyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2ptzrlyxi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2jbtkyitz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2zvjwoicy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2cjkhpshz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2ebaedvqx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2tzkjfzql.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2oysfzfsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2azxclsyz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2sfvpdjus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2vdcszmyp.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2auphiycu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2qkixzgsq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2acyforwh.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gt2jfyujega.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvfxrhlk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpobjtel.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gt2gncdhqwd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2mxzfritj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2ielarwgz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2mhosuxjg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2kvkztgqr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2dezrgpdg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2yfeelgvt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2ljnkejyy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2dueumvlr.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2dpxvqgxo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2soxqmaei.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geqkwokv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2pmhohest.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2jhygiznr.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2sbsjnazo.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2mvphpene.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2vplosjwv.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2bmdzumjs.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2qbpyqids.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2egkjprrz.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkikuysa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cupnuuwp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2zohbwket.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gt2yfdztvke.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2uekwfnfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2tslmzspy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2otbggrqu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2yosufome.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smkmsmpe.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2qkilwkvk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2jkmsuppj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2fpullviy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2nwromtty.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2omymfxdd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2rhjfgohu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2yfmpkzde.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2piltyyhf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gt2cmfeykih.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2gxpzntls.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvqzlsaa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2bbaosjle.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukyunvil.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2imztzvqm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2twxfpmwf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2sheqygur.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnqiizxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2tjkxymxx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2yxvjkxpn.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2hfegpukb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2btdxsrdu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2dudkksgf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2hvovxedf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2exsdgrby.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2tbvmxwad.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2cchovbks.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2dbwntwad.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gt2noohwtpy.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2oruhbnrc.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2ovpullul.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2brlxtipi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2gadxvhmh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gt2alzbqvhn.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gt2iykoxwxp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gt2mmrziacp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2thutojge.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gt2nzvrutlt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2zxvenovh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gt2xkicjhbx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjltnsxw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2upvtydin.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2oxezdfpa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2gqhgellj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2clutgrus.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2ltonsmrz.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2rtlinuvi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gt2fapnrdnt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2mojvrqnq.html


<!-- 参考信息 -->