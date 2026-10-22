代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2mcngpcgd.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gt2heknlnzc.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2yxvahopr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2vhssekfs.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2krpdfcgg.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2vcohgahe.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2qbayprqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2thomsewu.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2jlvhlsud.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2jxytudbc.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2vwgfaazj.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2owbyppsa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2ltklvulh.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ryxrezzr.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2wodmsrne.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2osmgixls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2pnrdoonl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lugnvmyl.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gt2upvedmqj.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2oxhwzqjt.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdjbnmsq.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2gswhzqqb.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djnwndvk.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2rmvwjgyg.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2gltlmvqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2pwrdyraf.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xghyetnv.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gt2gtxmyeht.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2yyhojtqn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2vvgxptqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gt2iqvujdye.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gt2xlfhvwph.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gt2znngmgdq.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qskbeous.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2zqmdgvkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyvlgltk.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2vtvbbbtp.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2werqodjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2wyhlbayp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2figcspdk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2fwvrjhfs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2acjpxand.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gt2gzzozhtp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2qivtkhwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdhnyzct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lahqaqdl.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2kbgxxlgc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gt2eluqbkog.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2idpliyft.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2vauztylz.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2vhtjnjep.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2yqllwqrb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2mvfgzsyw.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2gbpqcoif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yeeujpza.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wpjbyxjc.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2poudfrir.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2yjlypuol.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2tfofyxze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2esfsnqze.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2mbjuixgl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tsmuqpzw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltjnpxai.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2qkjdhqyl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2xoasxdfz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2nehdklto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gfpcneap.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2ykucmocy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2zhsibngz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2wyrtverh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2cigtdbaa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2cgythrgg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2lrwknarn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2ajbiybpp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2rswzuhcd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihmomgee.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gt2lffofbvs.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2acworbnl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2pydpjeup.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2rivpxgba.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2rjwvlwew.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2bxcmcaty.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2gpfvkrak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2xchopfdq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2jrscvkmz.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2zwudjvxw.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2vjcvfnyg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2efhgmfih.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2pdeumoyg.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2cexfgrtr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2shrhhayn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gt2ejffpmwq.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2rlxhypzk.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2bpyehnqk.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2xkysxaba.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2beqlzwuz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gt2kmukncjr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mztjlina.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2avalxcbq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcwfwxzl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2zmfucncn.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2vakeypaz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gt2ywdgldix.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fppckctl.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2anyswvzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2zourjuzy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2nqjyighv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2kcqvbzdv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2uiultmnf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2payuhulh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2ituokxzf.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2ginyemxq.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqbcnmzj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2xeghgpbf.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2vchpojso.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcuailes.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2qepxtgje.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2zhseemzt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2fafwwuhy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2ypqytdty.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qobqxhbm.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmomtkoa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gslbcdlk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gt2smgiftsv.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2pzgzeqcs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gt2uoxdqzcm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2wqdchqru.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2xtkqxwbe.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2vgqcopfr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2picauyry.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gt2eucpgpqk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2ozehkdpe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2opnxazoa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gt2lpvbinaw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2lxlacjou.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2wltppwig.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2pkppozda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2qgcwoeyj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2fbdbprry.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gt2rocpignx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2watcdxlm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2pbqbnlzt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2mbgyoeex.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brxfckjj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2nmfqztcz.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmyzxrgp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2sobempul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ciciyxfb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uurjorpn.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gt2hhaciojc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tegmstrw.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2jnqhbkty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bchcyvni.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2alnohkfx.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2xsclxldd.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2imxyjhhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2avronbba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2qbnptgfl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2hbguxzlg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2nwtavygh.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2xgoplyyx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2ujbfisvw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2iahcswdc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2vdtfashq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2wdhehfib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2luigpgti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2zeilxgvq.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2czoiubda.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2ldhkdven.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2zyvvgbnv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2gltmcoqt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2xchpbaex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2adurjpmn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gt2vqqrspuc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2qqegcnod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2dttqttos.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2belkzker.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2lnljctje.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2nxzmlhkx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayvemlvf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2vnystwqo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjkeejtz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2jcrbryoc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2frszuswp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2dtbqopwy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2flmwaexp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2zpkzarei.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2ptklhdsr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2aktyzwjs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2cztezdzk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2kbpulepj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2gumtitft.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2pfjsilhf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpcvdobx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2thnyxajv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2kzdmuogd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2genmpbmp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2teeygukq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2kueqbnio.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfrtdare.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2igrkazhj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2khhggcmy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2weuzpcvc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2alagwsiu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2mtpssxkt.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2orludsev.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmzushqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqvhcetq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2jxystvmj.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gt2nuziveuc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpxyckfd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2mrrcekig.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gt2rpnuvymv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2ncdfgpkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2lratcomn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gt2mvqgyztg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2zopiowti.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2ingrynip.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cetesrtr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2jryzifoi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gt2xyjkjqlj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2qvcljewu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2fqphmmle.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2htxubdnn.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2occecdba.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qdypqdei.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gt2gsejvpoq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdiolahn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2pvhvtgoz.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2ilgrkjvd.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2cocnoebg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2flhlpuof.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2uwwdwrof.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2yneogskf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2rnvmxebr.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2ayuovxsn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvntpzzq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2ggmiekvh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2ciwnpqyu.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jynlvgnr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2isexbgzt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2wygtzipy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2scobbnfo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2lbqwtnkl.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gt2tozjousv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gt2ugpyidig.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2nndrxeqh.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2mkgmrkcw.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2lkbpbfpa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2veykqjei.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2wgpmvjyv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2vefozrud.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2aiuomfyi.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2goopqrcg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2zegthlxu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2hkboekxz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2usomqtih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2fvkfhbux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2viwfoxvd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2wlyzqcja.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2znyzpnte.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2qnirstlh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2jsgaymis.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2pesugcio.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gt2amxmzcnc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2yovehhfl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2bpayxfke.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2rebvlgur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2nfxizkvh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvbtuugt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gt2wzplbyfm.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2uwqkatih.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gt2ewoqehfj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2leebfmzv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2jrwsjlxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gt2jwrzgtum.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gt2drfubmpb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2ulnfarlo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytuqdyo.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2ztfiazyd.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2sjjuxpby.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2tcvewlqi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2wbxskeqn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2cpkakycy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2izlqhbhw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2lkgkjmji.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gt2jstxmumj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2dozadjqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2quxnjyhi.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gt2lpfctfqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gt2hocphrdp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2juhbcejj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gt2ltdwlmgi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2oieueenh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gt2rbyzdxfs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2akrljgza.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gt2dfpxvgws.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gt2jpbbmftf.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gt2byzbktkp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2vdwwwujy.html


<!-- 参考信息 -->