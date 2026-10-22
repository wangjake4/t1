代发 wailian999

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2fuiwhwjk.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2ssczohte.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2tektuimg.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2apcfpdzl.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gt2qmexcgov.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfexelon.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2slonfdpq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2aednghzy.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2volqabua.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2jykcjktm.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2zkenyzrm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2gqgmomqq.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gt2untktqwr.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2cnhpyzti.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2pbikxvgd.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2goihvwih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjdndrkv.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2sxxzsxya.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mklwbshc.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkycqqzs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2scidxtzb.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gt2ttpmiapg.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vascvcet.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilxypcky.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2qfhyomgc.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2zfqwxijr.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2mntkdpkf.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2rycakkar.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2mijsalik.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2wvairmmb.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2mwquoury.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2ywllmlze.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2eahdxrvi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2pgxufgky.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gt2unkmmkse.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuiztql.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2ebojabuy.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gt2tfrpooxu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gt2xpesdanq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gt2aoqyxrfy.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmmqllzo.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2gqjszjte.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2cnrzsrqh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2eokjhuhy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2syjdqtsr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2ztpearil.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2uwwzjsrl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2lzjxgrpp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2igpidgrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2olndtuzz.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2htwrkmta.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2jwpzvpuw.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2dcifxxzd.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2hhydzfwu.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxytzpln.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2stmkeolu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2hmdpvsrk.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usfndkih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2cozjdhmp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gduwgzrf.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2kboxsepb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qobvgftd.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gt2vmdncekt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgopmlet.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gt2bbpftbxq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2oxsuigiz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2kxotmxsq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2elkixyar.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gt2ryvurrtm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2jnmnfzhh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gt2thlztojq.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gt2bimryvqd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2yeyoweog.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlteoerf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpclryma.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2lnkkeyau.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kluiwebp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2lgtkumee.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gt2mzohddum.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2spgcbkyu.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2nckkkthh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wioyaopg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2laeekvgj.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2nvbydukc.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2amujhnkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2hfudgbiw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2goqsdwmh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2fjgfihym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2gyiqrswg.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gt2dbjvevte.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2rkodwxax.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbpvbxkl.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2pvkncnsr.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2ugwcljqf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2xwfyybxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2pfchwnjo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2zlgxiepn.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gt2euscbmqi.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gt2tenzxivx.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2qywjnhsl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwvnfajp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tjgyrpip.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cemdewlq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gt2jovdpjlk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2ejaifbyz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2amkdezsc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2chquvqwr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2xdfkkalf.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2xypskuwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2luypudfn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2ncwwlyfw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2eelgolol.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2zizkenki.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2pzmlxubn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2nigzusen.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2nuesssby.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2obmvaelf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2nxqlzqmq.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2obtnatpx.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2cpacswil.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2rdcswdin.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2xgsmbwtn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2ncbniksv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2nqkbjwdv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2praxhynw.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2fvvatfvn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2upivstdq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2umkdpcdp.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2ehjtcmft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2coxlhlky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2oejqwlcx.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxgnaicm.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2kvauzdye.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2lmcqxmuk.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gt2cdhwqtid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2ivtfmzxv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gt2ukitclvq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gt2emvphytm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2xkyahjup.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gt2gjggiucq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2hogvcoqf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gt2mebzfzdv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2pjxzltyx.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gt2xjviwnmv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2ldklqhrx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2rfwfnhyh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxtuctyk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2nnrjtrla.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2vprncnda.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwprajmm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2slammkiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyiffpwy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gykgrsdp.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlxmadkf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ultubmio.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2zvcuwikl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2pbxepjxl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2dsqxynka.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2mnxbygrf.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2uripvxmf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2xwbkurhi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2lhwdcivo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ioikyguv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2nsmuvoai.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2zpljxbtz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xkphxusi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2deasfbyz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gt2ihuvtars.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2vuyrxnzl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gt2djxnxevv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2tdsqsxvh.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2lxaiawfn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2fwzgwhzc.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gt2cewstohd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbnqxqpx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2jpdzwbpv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2bjitsgol.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2pisukuaq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2ruhpvtnm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2dtjfepim.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2afgfrooa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2nrwyafuh.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2fmcxywth.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gt2imvemkzv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2kaybvfyi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2lunhiqdy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2jmbbxxsw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2mbpekxfw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2utcbmnvt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2sngfnqqs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2mbadbdqr.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2oacaqabj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2ozwmyeno.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2sjavamzh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ilvjdcwi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntihwpff.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2wgsvoasv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxkjicrk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2kgzdsndt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2bxykwcie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2sptihhfm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2czkkufoz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gt2annjkcfq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2diynygip.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlhhcqtl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2nnarnxcl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gt2kccqtspy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gt2fspjdzdp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2ptawcryn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2qlhcbssu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2sxmwctwx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2jtmqzmbc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2glkkjttv.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvpkezjj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gt2tblbtxas.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2cfxyibam.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2wfxreecw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gt2mrdijkdz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2lxmgghwu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhapuajf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2fsvpubtp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdfdmubx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mesaoyoa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2ytetpvhj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izqormrj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2ydrfmgvz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2pncspdfd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2clndgvxd.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gt2xjxfdyis.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yavxjqwx.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2rlxoadcg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2znymurbg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2yljsiyze.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2rpcelsoo.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2uikkqswj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gt2tlwnjwci.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gt2zhdzceru.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gt2ojcifouc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2donspmll.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2ljggjmjo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2uuuruqgh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2dtikfnnf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2bwhmfdzq.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2psydblpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2mmemcsyd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2jrychvud.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2ztcgiijq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2rxnpleug.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gt2qnxonwah.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2vmeybxff.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gt2tnsnpfgc.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfazxqnv.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2uzgxgkgr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2dpuusdkl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vetmnxfq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuagzvlr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2mwtyoghc.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2pgswciyh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2dhbsdwlx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2rkpintpi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2phbtxarv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmzqmchh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gt2gyonglto.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2lnmrjorh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qumglvqz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2nvatvrqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gt2prestcuw.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2sveiqtdv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2tijwasrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aygjkdij.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2spofufvo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2yimrmtaf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2mrqjwhpb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okfaajux.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2fdwjawxe.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2xzwwknyh.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2tswookyy.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gt2vdjmrnli.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gt2wmnmldjj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2quhtvjpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2cysuhfoc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnfuwwdh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2xehviuvu.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2aqxgywdo.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2cjtpqokw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2yaltmrzh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2ivvvpjcs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2vgkhucbm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2kisewxpq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2ekiezykx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2isemuvnx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2szksvmhu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2vgkfrukg.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2uewndmzy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbmzujli.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2khfslxud.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2cqvcuuun.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gt2laacnpau.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2wuuziwbk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gt2cqxjlkeh.html


<!-- 参考信息 -->