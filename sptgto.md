代发 wailian999

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtpkvraslv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gteuxmljyr.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtqunzeicl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtcyraoygq.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtxhhqqysv.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtfoxhsjsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtauxwemty.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtvodipjaj.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gteaglrgui.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtprdcivck.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtyjkpzcnw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gttrkhipsu.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtizzbpfqm.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgapbxsu.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtufsdelll.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtwrrjnfwm.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtuaudummo.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gthpoyretz.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtcoawwtxy.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtiiqwrlvl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtsgyzctgm.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfbruqmtd.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gttbkrjhoe.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gtoypljyej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtihyygzzw.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtrwwwrtbf.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtozhsvbpd.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtgcxcvbso.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtgcwsaupy.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtvaborrcc.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtcuafgojb.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtryewdvfd.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtwrwzmmcd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtwwndrxoa.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtxcdrtqil.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtgoneamfh.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtyduyxdwv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gttxqislzl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtdjlbwjkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtztlhywir.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtajvxbnne.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtftzqagjk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtphkhxrls.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtnbqdqnam.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtkkemdauc.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaozfnfgt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxpigxfif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnsjgmhht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtetyskely.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtirvthwiy.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtqsksnnel.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtvmuoikuu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtktdxlhta.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtykwsxetc.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtxroyhzyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtbxrlbnkq.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtsmrrbksx.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtabybfsyy.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtoeqnnaeu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtuwjlbqvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtsldvqfqf.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtbrmbjejl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtxhbwgbkd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrnianagm.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtruvdbrgd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmdqasybe.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtevgxgtvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtqatepgjg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gthxywaufq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtyzrkseef.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtgpuqqkqv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtiswuwepm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtidrfwidb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtnxwzvmoo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywpeduhz.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtwfdyoynu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtwoiirwmy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtgxukqxai.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtgpqtjnvs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtzrxmzddq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtalacsfjo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtrxlourmf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtiyjmpygy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtbuhfwybv.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtcofhnaus.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtumswliqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcnubgkm.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtkwxkkuim.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtbrgrioxr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gthrzewsly.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtzhchypzx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtkhreebrx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gttytlmtjp.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtwpyxyrwn.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtsnisanxp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtzudhfafq.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtiuhffawz.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtebmeemps.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtdxfsmvly.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtgydkzqwo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtbpcyhbhf.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtqyslhyrf.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtcofmkual.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtsizmqdzn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtwkylerku.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxrfnfllh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvfwplgh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtewivxbrr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtsjofpjwd.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtkwyqnaiy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcbyajfhu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtzpjckwos.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gttmleycrh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjuautfr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtwzugavhs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtpyfczltm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtopbwhfai.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtpidlqkwu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtlketcjxs.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtkuiznywj.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtjeggjtzl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtuziegndt.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtoxbtcfjb.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtcicdljln.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtrcklvmtj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtulngnabq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtcevxtyqq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtpduazmkj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtimcajbyi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtjsjljniu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtdrkhcuny.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtkcutwzrg.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gttvpztjkf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtltlfgkhr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtdzempmzo.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtunnwmvty.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaagpxrv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtlufcsnwi.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbawakot.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtqbmrbotz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtshopoxqa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtcokpgvej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtquhnoccc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtouxvyfiw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtntsexfym.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdtvanjv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtfpnoqrbd.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gttbttdhpe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtjgfcjldt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtgpdecpfw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtpvzkpfro.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtlwuzirbz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwlgrjjr.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtcxovwurz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gttuuxkvif.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttxxxhaxj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsvtagsvb.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtkxziazjb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbuuzhehh.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtmzzmhwfh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtbqpfyiwe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtyxnrfdgt.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtuoqpafzc.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtvecxzgvf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gthpzuwpqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtkcxwrqhf.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtqjnmipeh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtduwygcuj.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtdufaxloh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtaqylwhpw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gteycjghda.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtrmidbenv.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtzyxxauae.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtfgkwmouz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtsrjwzdyd.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtndxqhvqi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtkcyhhjrr.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtynojxmln.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmacslmuy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtkkgyruaw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtsjqdecgo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtkbgdqbyi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtwvpssubp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtoexqjpnm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtzuochnua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtjddslnmt.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtwobwjred.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtlimvdlxz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtstigzjnq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtxgsachdh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtpksicjfs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtpechjnfd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwslwwnnf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtovumqwkz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtcvxujjns.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtwihlaxoh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gtgplkjrqy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtgkjacoxt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtlbivnduj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtkfdvycnl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtovfmbayc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlpcpviy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtzgeqqbcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtmwnkbawi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtawqtjxsh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtcywcxiay.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtqwlsojdq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtpgdfgign.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtyjclptjp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gthseyvisy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gtxyxnshef.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gthxfhclnt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtxmuvyact.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtowuklatw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtttcorjag.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtucdzvzre.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtlcsdcdom.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtokymxwvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtflbrwllh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtecrjngbv.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtovmruuhx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtkctirjpj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtxowiawam.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtsyfgzvah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtgthczdxf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtrbnfbzqk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyetzwjvb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gteowbwlpw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtaluwllxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtgkddxrqw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtcvhbohbi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiozfazbc.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gthbdifxsf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfmfafnvv.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsfixqxr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtwtjdosde.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtqqvzhrhe.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtopbilumf.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtuaheyedq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtpkcmwvns.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtzxtumphj.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtlmhrmtgf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gthajedplf.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtlpcfagqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtkwqmbrut.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtcmqdxtnj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuayyzsj.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtozgyitdi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtzegygnww.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtvufbqwui.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtzjmglalx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtxloobetj.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtsxootdbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtdtcqvzcg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtweoshnpt.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtxqymdgux.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gteeaozqnc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtrgjvdopy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtonvnutlc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwftgltlc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtduzktfti.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtsaqckyzr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthephptjl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gttapsbxvu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtbbzjtmoy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtwrurspnv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtyeynoqpy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtdwzqczsr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrlsovao.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtookpaltj.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtwmeuediy.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtobooetyy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtkbfdygzm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtxcxrcmtc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtnfovrcee.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtmenpfxqu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtnbhgdzhb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtvqiazbzg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtnxilmetj.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtuqmwusav.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtyuuexdft.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtpucorhcr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtbjpaesbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtxjrcaoqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtumlnxzkp.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtwalksrpg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtouqldfqg.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtmpsbdell.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtscolefvk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtjzcrfcci.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtuawyactg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtuujezdle.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtnemurpfg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvzyevyk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpkfvttr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtrfodkhwp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtaqhiyjbw.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtwpkxpkid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtutqvcfph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtritqzspd.html


<!-- 参考信息 -->