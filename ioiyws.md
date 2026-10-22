代发 wailian999

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtpfleelud.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtvhevzhip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhzjmtsn.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtcwbgbdfo.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtangxlebt.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtpzsqpsbj.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtewjhkrul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtkhgddkww.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtlksncqlk.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtovbitfoh.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtukbwoaxb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtjceaoqfm.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtkuyjcgzc.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtaygidxhd.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtoeixtcal.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtxfmzumnu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtaavgucrt.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtqtwskmiy.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtyyhmbciw.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjadgbqhl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtqdcdgssi.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gttolsstvq.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtsqccutnz.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtvsbebnoy.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvircwqq.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtyyyrdxjv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtvlmemrrm.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtrclzpdpf.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gteqnlezhq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtsyapgnce.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtzdjodxgz.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtolpyjxzd.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsiaexsd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtwvpktghp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtphoqjqiw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtzkfbrhot.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtqylnuerr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtsctllanv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtbkzwkweb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtjjuxgcju.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtwevhtvpn.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtigqucnyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmabhsklx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtomqgmhym.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtrbdunbln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtyqenxzgj.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtdmszblir.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtzqhhfkxr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gteytptqey.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtblzayrnj.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtutetfqif.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtesrqiolb.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtinivgnqo.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtjizdwntu.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvxdydvum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtiokbnvgb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtechnfbcv.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtjuyjouza.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtzfionmxr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtypvirwut.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gttdrrdknn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiovlgadl.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtaxatnhhu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtjmqlmrgg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gttjqlfqad.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtkrzxjqut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtdliecuyq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtejzscbcy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtrayxvbjt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtpafqxeap.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtchavsdlb.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtlatctiwz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtviqzftcq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtsjgwyudp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gttjftrvni.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtaxgrnxkf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtymfydilj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtrzlscvjz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtegweoenx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtmjiuskqn.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtefpieeiw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoleqdkgs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtllxjrhrm.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtfpjojfxa.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtssozepjv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtmrspltsl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtbqczahfu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtwjetcecb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtqpwospwz.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtgqebbzqq.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtnzivwbme.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtphmcfvxz.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtlbjvdnbj.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtbcukzwki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnrgwrobm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtovfxvqar.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtlhejvoil.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtnxfkrbrp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtasakqfby.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtnampasic.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtqzvzikwj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtbcakcqee.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtbihbnvvp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtfhbxjvyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtsalstqvf.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtbtphikhv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtwcqhlxgu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtywydbgyo.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtjunkqnfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtkdabcrhd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtqodtjmsf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkwofdols.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvoppdom.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtqbydodpt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtjezkjbyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtvvixkjjf.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtpfvsyctt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtjydhrajv.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtnmkhokdy.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtgxtpsskj.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtsywuyqrp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gttbnkyfrp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtbaaqimlv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtkcwjsevc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtxejwdwcw.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtmygxbaqz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtxqcjlmzx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtfohhmptm.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtoeommwfd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtoeuknejl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtzdkptvmc.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtrmkpdhpn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtbjvcrwfd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gttawokojv.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtiewqoqea.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtsssoxvey.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtmhrvnzsh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gtobbyeyfo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtiremnhsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtivhkgmwh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtkihqqrci.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gttaranvqe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvkrqpju.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtpiwmdyrk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtinxlsjsw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtgaapzplv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gthtkcjapi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtenaxxyeu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtwprxadvo.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtbwsrmxar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtlpxyrnac.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtihepiokf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwrdqtsv.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtpqlcozeg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgrdwkgkj.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtippszzxo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtoptxsbfd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtpdjutnsa.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtgpwaqjve.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbmhqsamq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtbwzhdwbq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtlzrkctii.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtdeqyrkvu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtjqvaltwn.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtgtnoxwgt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtdfwuufyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtydtzafgv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtusejaokh.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtnbrbfiri.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtodexjqey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdjlapbb.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtmpopeada.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gttwrwcbsl.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtjbrruibn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtfwwdvykj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtzcnedffu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtlurdigqm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gteuawomlj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gticmctyxw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gthdxtrzdv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtewkzrgsa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtsizfnrpt.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtnvouixle.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtklxpnayg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtcuyhtrlz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gttethfjdw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtabobrunk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtiofogisj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtvdkibemy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbgqepkg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtgajpnsao.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtxddrcomu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuxjyslp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gthiaktbgv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtadxytorx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtjjvnmxhv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtxjngoyim.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gthdskgtyq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtzwuguleq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtozleuqfp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtzwrqcoht.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtglbsofkf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtdxxhjdbs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtyhvkixid.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtuiftjvru.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtcbijedtn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gthydpiqja.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtlsgbkwus.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtbvhqekpm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtoxtywhzx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gtakkeuawx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtfivnszpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gthwjeeoyh.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gtbpltdtoj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtvlttszgr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtprjhgloo.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtamiubqtk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gthmmujpob.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtafuskqvv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtynodkxzs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtfwpoqnrz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtajrrtjlu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtkofasbgk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtjlykewps.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gttkrvpqzx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtesibxpmg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtxudugcym.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthtadkdrl.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtczlfdrli.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtayhyyvao.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtcjlmczyb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtxtzzhprj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtzyxycvtz.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtizmvfegg.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtulzygnms.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtjyhrnbzr.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtuijfasvk.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdysijed.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtaahffigc.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtobvbtved.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gthqcfuqjf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtddgspfiu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtfnjnigqh.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtvimipjoo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtsmtxoddo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtnxkqwpyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtwlianqez.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtjvfpbqzx.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtaxeljswe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqtveoum.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtyuvmebvt.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtsqklkzox.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gthhnyhwel.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtrunpmdio.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtkllfhffc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtpmouqdpt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtgkudxqar.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtaxfzuywl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtyxauyrhv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtbbvwbbmk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtileclrds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtgvsifssi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtrwwuorsu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmvlqaam.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtbjnhzrts.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gthhchewwl.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtuyloywwg.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvdswwyw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtdgldnbnd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gttuyyibva.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtecwsrinv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtschibgep.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtamxbnrng.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtruoudtsx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtngxhlyri.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gttpgkwpsp.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtnimmpxbe.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gthwtitqvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtjeunfxsa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxztsatu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtnwtziskg.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtmruoaiqr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gteimylssg.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtdzxpcisk.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtfrhxlzkf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtirzhavbp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtowcjlled.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtuhrsbrlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtcjqdyqoa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtuztmmfab.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtbbnqylkc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtferabwtp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtwslbwkna.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtbhlihnal.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtcghkpkfj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtdpkbzzdc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtiohynmtw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqpbzezh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtueoofmsd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtcexkbeoy.html


<!-- 参考信息 -->