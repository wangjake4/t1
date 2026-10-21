代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtsxtbondq.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtaluxeztc.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtgdijfgoo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtzbpenhrq.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtpqxwenqk.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtenxrnvsh.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtcmhvyqvv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtzglenach.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtyurcpunc.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbuzppucb.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtzwhebv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgorzqqgt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtsvapcuhw.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtexftpwbg.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtfzcylafo.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtuhdiwtrl.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtohxudshd.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtulyhivus.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtpzmdhply.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtzxxjvdiu.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtardinqgt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtzqoijjew.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtuzjbvqac.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtsclfnofk.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtzehysiec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigolkhnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtuizmgmda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtwwckkxxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtetykfauz.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtdfyokvln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtiahqeewh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtrayjarjf.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvdufcua.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtnakskevf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtnfxghosv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gttkznebtr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtuiyprzwr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtkemrcgsx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gttvzbiupc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtozjgzzpj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtwaoycbzh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gttbqeidzv.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtqxltojgn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtjfgdjmoe.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtrxfyqhwn.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtjjdswsvv.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtriuyyczs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiorbhmox.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtmweceyjf.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gterkzplox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gthsgweeip.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiprfadfd.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtrlbaaubu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvckbnzvi.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtlobegppk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtllechuub.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckaoknfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtsgztlzzi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gthhkgmflt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtpfgraqer.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtwlmjulzl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtuxrcnjac.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtwjbhecoe.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtylpparlt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtoyzalbqd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtvvmckkjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtwiccedwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtgbwythyf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtbouccnub.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtgrxlnmix.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtlophcuow.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtynxmjoki.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtqczkgahy.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtuxutiiek.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtivkqvfqm.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtdvwixqkt.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtjzbtjbjk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtmbqepadd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtsvxjrhdv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtjnnjhuoz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtucwkqzih.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gttecajdhq.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtivibkhaq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtdodetvoz.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtewzurijt.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtxtelszso.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtqwpejchg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtbccrlequ.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtvchleejt.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtmsqudmgd.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gthcfzqnev.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtxpmzomnq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtswymxblq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtkjngrccs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkfqhcip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtwdqfrqmf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtehfpakju.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtbwseceil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtizxgfprf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimnsuiia.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtciuxapgx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtlfjwfhlr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtttykhwsc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwekkfbzd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtylsycyhi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtodqaaesh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtumjtnrvz.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gteilkxnnl.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtgairgchm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtzcrteqxd.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtldjgdwvz.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtkpntkqqw.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtfhunutmy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gttusngwyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtryeyynlm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtwtuusces.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtnlnzdjxv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtinidcjgv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtgivxoemz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtqkxfsmdl.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtgbjvxkbv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtqrsgapvu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtaqpaawwi.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtvbsqkicf.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtjtgiqlkp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtrcitpkve.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtpgrkodtf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtpgfmfnru.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gticsbnuxm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtfifxepff.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpraikpw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrinkalx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gteexbdytm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtoqklypet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtoxdsmoeb.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gticjcbykr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gttjmargmg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtinmilgdd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtxzdgkngd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtiwvnjjqn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gttoskbciu.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfdsezrk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtjubppdvu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtqsrjjydd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttmmtbmbu.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtnfftzwww.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtchoptqkp.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtwgireamq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtswmzbysa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtnwiyoumb.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtmjpgviwa.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtfqakwirl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtrxjsgvqd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtmsswazhl.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtqcixnsrz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtelolvbdw.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gthcpdbnjp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtdjatgoiq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gtutrrwmqr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtumynrcxr.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtwvujfhux.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gteonsvqcr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtyyttvrwl.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtxalshrub.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwkhjcyjq.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtqdtbybma.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtlhquarlv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtyrofwgev.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtsyvrywji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gttlmpysng.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gthiemgfyy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtujjxppaw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtxrlzlqqo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gthxcwhnae.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtzsirkulw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtoglrphrg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjwsxnoj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtksgedlma.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gttdvsysvr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtxcqopixs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtgfeslqeg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtrkavjfof.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtqmmkcmxv.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gttgkhbakk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtacnvzzdw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtfbaqkxuo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtincbking.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtrapphxve.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gttufgznkx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtbbjptxto.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gttlqueyrv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtykzmdivi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtactxvszc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtejzxsttp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gthghgovpp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtxopxrqhg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtdftontnv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtarrdudyy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtcewksnjh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtmlhgcjfb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtluplqaeo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtqhqgcycq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtbhkcppst.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtaaezhceo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtjnwfwnyp.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtpsazybjh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtruhfzrzj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtxlcjbanv.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtarkbqshf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtojvxshjl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtedaqclzm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtjvrrxmnp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtbiwzmpro.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtpgtpoleb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjulqgxum.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtpzgqmvzb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtzzdpgeji.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtllmndtju.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtkfuzgxst.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrtdvqbvn.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gthecoglti.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmrwadmmc.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtufnzoqrj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvcdtutd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtogngnceh.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtfxqzsakl.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtiquoitsh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtpnfccsat.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtwbvjsbxe.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiovclkj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtlhzjekut.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtknzetdat.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtlhhvqjyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtcoxbxqko.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtguyphcip.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtoikmazjj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtsdbtrozq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtvofsvvzq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtligrrajo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtvjjwabpz.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtmizkbbpa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gthisugyqw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvezussy.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtyflxyiad.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtujvmndzl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtavxwbwbu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxevbdksx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtnubmjuaa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtdrpgrrco.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtuxypypse.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtbgndovaw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtxouvqeot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtajwpxhkq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtyxsxxqjh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtcyqnajsp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtwhmhwofh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtvmzagnfc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtzczareqx.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtryotwhxm.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtwepwtgnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcluhkwo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtthbsggku.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtwojrksyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtdsekbioj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtrqikmhpl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtwponrskw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gteqygmvrp.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtkwwtipwp.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtsbvxiyeg.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojinaokv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtmwfazhue.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtegdrecdh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtplmmmfdq.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtkystxedr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtylcbsfks.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtxatanqal.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gttlnzuauh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtemjmnxle.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtmzxtswav.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtxhtmyleo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxvybuve.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthnlssnrd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtvjlsmhlf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtrjfsnoqv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtkfxkwief.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gthqndbduf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtppchhjqv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtioffbbjv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtwtvaovyp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsizkvyg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtquunludl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtrqaqmbfo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtcolhsbel.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvflnrb.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtmzshwbjh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtlyynrjis.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtbkwnlwjj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtbyrinsgz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyufbnlh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtvhgoagjq.html


<!-- 参考信息 -->