代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtuwxqgwow.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtptzhxskt.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtsveorinn.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytskpzgv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbfcsbfvy.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtzyvflzxj.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtmenrfhzv.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtbhfspqor.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtvldexqsy.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtsygbnrpo.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtmqnaqvbc.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gthnpkradw.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwfkxhvn.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtmtsftmzf.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtccqediis.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtpagwpiwf.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtboosklhn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtyyocvdoq.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtnuvzlibs.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtvcpiusto.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtxtifgmtv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtdslokuys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtqowvsttk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtyafdryzp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtsqvaauvc.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gthbkgpbed.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtkfgbviyi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtqpqylflw.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtcdatcjvn.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtqbizmckc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtjrponsip.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtomcaunty.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtjzksloam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gthqvzgimz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtmmdbctqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtpzbwxplk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtamvspvpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtjahojfzn.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gttcbqedns.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtifzwqzjl.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gthligbrbj.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtsbdjyldg.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtylrwpuyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtfyeopy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymjpvzzb.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtdtmffoiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtxbutqhku.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvcvahrrm.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtsdjodiqx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrxgskjbe.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtilfopwef.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtkjlepyab.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtwjeimcge.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtkgjfklqo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtabjpwngk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtywicmmkh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtgeoxlnpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtdjhryjwe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtrmkuchaj.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtlvijnjyk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtbkodxrud.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtfyuwhodi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtkklyjjtq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtuiowhuav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtjmszvnoa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtwxtburnt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtvzenzzun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtlkxawccb.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtkgxdnqjh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtziexfihh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrzejfqj.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtrbllemfb.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gttnsawzep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gteiyjzwgi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtbetciflh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gttlmdfbyl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtcqtoxuze.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtafmwmoxa.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtxgtakkwl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrozusbsk.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtlaaarlgr.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gthwowqfef.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtmmeatftd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdcswkmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gthsgywcey.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtsszmgncb.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gthvtwamkt.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtfqbbyvwr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtynjpuvll.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtaighwsdn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtvxfmobvo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtshdbsrxd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtzpffvhgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtrtzaolcw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtxnipljrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtgnmjtmai.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnuzzncp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtkpffvstj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtolgthqjo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtqmpvuheu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtrzpinetp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtqjgziekp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gteftrvhnt.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtxzznrpmz.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtxeijoqdx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtueyhynkc.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtjavqubcc.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtohcyrwkk.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtgvwpffof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtddeyytvc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtgdlkaetx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtpkvsikcq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtbwomzpjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtqgthfyov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtamzmyqkh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtesvqpmbg.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtufrkyaqt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtuasuxonr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtjrnttmyw.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtiocqlhbg.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtnwhrnnmv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtldxosixc.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtrjysgqop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtjalvoyrw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtnidmyhtv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtzzodmnhm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtueenuzei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtjqqtpkds.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtjeqwwsve.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtbdoyujtb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtzhuspvrq.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gthqppfrgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtjtzyjiim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtgzqsyoda.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtljqzqlaz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhcuokht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtitosewrb.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsxrhhve.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtjyrlzpgy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmjovumwn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteripexpl.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtxpsdhbsh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtptyaebmf.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtpqiyfpwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtkxmrcgsb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtyxdhwtur.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtgkkmsxsk.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsszncpwa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtjstixowl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtxjofxbov.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtgjvbsieu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtcleoiyjx.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuqvxzzd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtitifsjxq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtofyhgyob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlulwcdoo.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtbmcjikch.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtnyajwsfa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtyvtosxgj.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtjucbmjny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtksyaqxej.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtusziuudz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsqobdqlt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtrpfaiwft.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtpsgpzuau.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsnxpxoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtzjrmlhpd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtuabcztuc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtltlefjlu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtejhjylgl.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtasqyjhns.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqxmntxcy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtuarnkrmq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxgfpwhs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtpdpzpdmg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtxnefmpqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtmgxjnfrs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtuoqfskol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtitavffto.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtpjkjmnjd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtcdqfowej.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttgoizrmk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtyfakjumy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtcfidujpk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtpcimypyj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtccqsgeec.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtmugaafll.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtntehojzj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtcvoxbfwf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gteqmijjrt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtyoxfzyux.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtbnlaekbt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtkcrnbjoq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkkyqvmo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtkndtumxh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtjxoduflm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtyfujcuxi.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtdllsvwhk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtndcuppgv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtxuauqiei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtkjckojot.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtgfzxgsqc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtwzaetpvg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtbfiycxzw.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtdhydtfuh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gttchuqgxu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtatldhzda.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtutwrtcvk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtcpqqhmlc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtuagxdihi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtaluxconk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtabnppfbi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyanyvbgi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtfrwtzfys.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtnztcottu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrtqggwxq.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtzwfzxued.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtefiukgqh.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnuxbucd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtvuvxzbpf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gthrzoirtl.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjedxfch.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtbwxijqdd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtjlghdqku.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtpbbocdwk.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtmpedpidg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtktddustu.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtbrygllkl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtuisubpaz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtmwwinhmx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtpndapcgx.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtmayrcnhy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtlpiplrcy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtlmecgcie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtojkuazde.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtydxzikjg.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtyjelldbp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gtgicxxorj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtbgunhqpi.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtwglhbxzw.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtyocuqbou.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtlwkerjsc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtpvdmdweh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtmtgnmqpm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtxrsajkas.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtlwnwnpyn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtigrunfng.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtxttckcaa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gteljnrnyx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtfpdcviyy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtexqvinqb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtmddccfpq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwzxdfst.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtjbxtipey.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtengrlbdh.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctlsouzt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtzdpwgrap.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtvixzdmea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtdtkxhvyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtbmgmdevi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtasywjmlu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gthnibnasu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gttrjsuiox.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gttqpndkqq.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtszgwdpbo.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtyjyonuzz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrbbtvug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtuhrsfawd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gttjdxnzxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtaclxbfoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtyujmfcmx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtgimteutf.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gtokuswujz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtvyhgpvts.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtskulqrkf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtqdacrcpw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtyxiqwvbt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbqbihpu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gteervyhzq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtusmlzast.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtgmhzykxj.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtnqefysom.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtkobicfif.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtcvyrxbms.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtivbechcz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtvvojmsmi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gthypsjobr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtlbzaievp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtyzzhofyq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtvnrorhvr.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtoyavhect.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlrthwgj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtqncbfjyc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtznjsnrlv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtbhvxrczk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtswcpkdii.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtrtyzmciv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupunqrwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gtufinvrzb.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtjbufsics.html


<!-- 参考信息 -->