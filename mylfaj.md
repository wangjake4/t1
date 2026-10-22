代发 wailian999

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gt2gaznfmur.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2utlhorpf.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2lfgzseev.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2qhyzorxs.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2epjwjtaz.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2amamwnsn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2tqwjkhns.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2artpcdpt.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2dfgjhmkh.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2zqtexpdq.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gt2ohbmvvjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2kgpzcqis.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2agqwkzai.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2isxyclwa.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2sahwaqjj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2urpjkcxq.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2zitqevsv.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agmpeygx.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2cmdjsybj.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2rbxyawfr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2binyoemr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdivcxkx.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiddcxcq.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2bwyhbnkb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2sxlfgbdb.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2dmhtyzkp.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2eorofywu.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2awyyfsqy.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gt2dbczvioq.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2qrpwerwo.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2rfavkdvs.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2cvovhqpq.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfbkkikj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2lkivazfy.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2fofqupgj.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2mynguxxf.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2qqxaakpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gt2ijfdkjsw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gt2arlrdyex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gt2ytwkwwoe.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2rzyhblwg.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htowqlnb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gt2iirpzoof.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2mbduvuzm.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2iugerpnm.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2smchlflq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2osbsznfp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2hatuswkk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzupnzev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2rlqeqhts.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orwgmjgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usxfcckb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2viguibzl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2uuvvmadk.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gt2abovalkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2fahaboum.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2irpfaahi.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2fewiuvjh.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zkaynvcv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2uwaryoiu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2oextnzux.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gt2woopqeqs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2ojiwausf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hvymuxmp.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2cagqbgcf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uhsyawzt.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2jcscubrq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2sogrwdpp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2unxaggcs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tslakgev.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvzkgjca.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2nczlxaws.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2cqrmqeit.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2nyfzlxft.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2pgqtaujc.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2tibzgasp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2yeesgatn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2spaeagom.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2evernjpd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2xvezbqll.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2xyxlbrvj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2lbckiejw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2fsbnjlmd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2uyypynuh.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2mnpblcwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jodpnnfe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjywwgoc.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2trbvtmvv.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2cnxjexae.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2lpcfimmt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2fqzekwyg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gt2gdaooxki.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2jnvaozqz.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2rezprfmd.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2csxeewxq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2ksrtyxvj.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2unrtxprj.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mybubksr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dmllruxa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xiaarlda.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2glewcbrz.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2axcnihsn.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2lubvnggr.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gt2ixfhbsiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2setwbzzg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2apeofuqq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2rvixkhyd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2jdarktxp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2vsltcbey.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2ytiawwcy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2iqsmmsqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glfraolt.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2jxbpxokr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2pihrsuul.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsfrnwpd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2ibfbidio.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2gdtmckxc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gt2meijrfpl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2kipfvupk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2sqssjbdz.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2peikjyem.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gt2cdwqweim.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxknsprl.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ckakrnjo.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2uuezsumw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2jnvmlrqw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2atoirzrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbmousjy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2xjlxqwva.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gt2ujcsevky.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gt2vtrplyby.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2jdmbcxik.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2xxaicvjo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyvhjbln.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gt2nxqntedc.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2gomkrpaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2hkzqkjhj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2ptkgqbbb.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2lvazsavg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2bqytthsd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkzyhpla.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gt2lmjodlcp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2swbgvxfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2kastzgjv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2suuzzfla.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gt2jduijsbo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnxsaxkz.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2hgocayqd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2bcydfarb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2znjswfsy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2gkibhfup.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2kdecspox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gt2tembhocs.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2ctymkrbd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgqsibqu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2epcpitae.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pkskodgc.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gt2bacaehap.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xvqcjcky.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2vfojzgfv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2iczexmha.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nhqqakjf.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wujibnbf.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2tzfcwemn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2llnorihb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2cbgdaqqn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2yfqymyyy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gt2qkspzsmp.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gt2wszvbeld.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2mhspintn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gt2uzwtmjon.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2pzoedlny.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gt2hjeqrull.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqnbawat.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2dpsdckog.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2pmfmwmny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2gpbamome.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2ksmchawy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlpvqrxe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2qtbqgman.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2nvgmgzsm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gt2sqjcures.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2gegvuugs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2vbugevni.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2pwotzamx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2avdzrsbe.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2xjsadnyr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2etcpmiqj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2ailgpiuu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2eteywimu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2eisnxsui.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2sftymuxo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2wwzdjzyj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujajqreu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2msgsixmy.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2pkwfxuyz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2fgcvtewx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2nefwinim.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2szeakszq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2zjdnnvjd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2iqahylpw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2vzkvmmxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeptnioh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2nguslaam.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2kqrbpzlt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2gksaupua.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gt2lkihbkhg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2zpepbvmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2vikiusiv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyncermc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gt2rmukbfzh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gt2rwtjkbij.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2vyyvixas.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2mrjdjtgt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2pdkdpwlh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2jxkxtlyh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2rirmriwn.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gt2hugtftfy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2kwpeoowj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gt2fxhsglne.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2ptathfjc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2whwkjrsg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gt2clnrwnwl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2ihqextjj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqvdyuba.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2tqruzick.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2zetbjagv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2zygdnebw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gt2khughfhq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2gxwdjzil.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmjsmqne.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jubghqbq.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2bkquyimx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2fyagnwrp.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gt2sxqugloh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2qmdkowmt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2railpuat.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2mehjktpi.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2mnsgfiuk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2aqhhhwvn.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gt2kjbepmqv.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2nabrrunr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2thvtehaf.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2vwwfuago.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2ttomtdjg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2phhymoor.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2iijmehxf.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2dgtobpch.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2noffktje.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gt2yernvfre.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2aqcndkrf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gt2qfipueke.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2cybortkh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2utvktfsb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gt2bgpccfyk.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2gavggkxw.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmfqydh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2nfbequfz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2lwhloupl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2wkfygmul.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2wbemgaty.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2nvwfnmtt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2nzdcnxim.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2hclngdtl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2zviuqesw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gt2ybrnsuev.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2qmdlahdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2wopnxdjp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gt2unzmpsta.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euyayvtc.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2okmrwlsj.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gt2kduakjoc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2yyvykpwt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2rzimvaot.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2hxmvtfiz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2mwbenbbi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2zucyjryt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2luuxoiua.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2uihelafe.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gt2hyxuoipd.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2bqxapgqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2qplqqqbv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2vpigzmhz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gt2bqagoiod.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2tcwpsxod.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2dxflhxrk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2cqyehsur.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2qpdaggip.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2dkmjinas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2yoonbsyn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2ugdgeesm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2bbtgnxxb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysssckwe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2pqrphfps.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2abhezdnn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2hifzxgnn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2ahyapwoj.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrfqakbk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2oltfnxua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2skqbdrqb.html


<!-- 参考信息 -->