代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnskmqbmr.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtazlpogei.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouutnjlo.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtdlkatnmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtgrxxspwa.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtgxnxhvkl.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtejlcvkua.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtopcqajct.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtukvhoyua.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtcgdvoiaw.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtlcbbgpcp.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtyaxdsgso.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtiaupjcyp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtmebevybx.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtjlauhmzs.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtjdijajna.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtcjqqvtgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtqsmvgoxd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gtqyvapjyu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtssjljmkb.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtzxybnkxi.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtkdudoxps.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtvinmhnji.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtveidfuty.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtbnuyfigu.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtgpgsxspe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtdffpgckr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtmbljeuel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtvzjhbrse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtehzdjoyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtaobwzmiy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtgrnnfkir.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtiefdcwwa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtermkwebm.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtamoducpl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gttwxitkji.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gturlpwzfe.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtjjjqijvw.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtxiwnvbup.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtbplchzwf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtenpofjmm.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtdaywktde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtshrkyqrn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrrgdhfyi.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtplwnbexj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthpppgmfz.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtzayzuhci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtixkhcjtn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtqnmdwagh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtemmejyih.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtyelgvzfw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqdrdywk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtgkpbjlds.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpanvslw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gthfpalyzs.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtrpjnyrxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtjnhdbgpo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtcspbauug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtknscyznw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtsixrchrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtwrcflwxd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gthirigduc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtmjjkmgls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gttpcxymfi.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtuxngxvxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtzbrtfpxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtdbrbittl.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlwhvvsma.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtuvkgavpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gttemeuite.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtpwtzyaly.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtsrnogrzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjjkpdwk.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtylsyvymc.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtsxcplyqs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtiketimbb.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtkuzifscl.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtxtwukfev.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtplsuhiae.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtsculujai.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtrsdiiamh.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtvazragsc.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtufijxgtz.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gteolddwzv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjqedvwlm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtuzegzmyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtxioaujyc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtgeyxidud.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtygxtczsa.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtsnohsirc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtmnpnfeve.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtdavnmxmk.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtmzkcdsjy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtsygdxwpw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtimjqgsvm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtzxjucjev.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtgiejriwd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtvbwmvmck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtqosdyssh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtooqyptrf.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gtukjonskc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtktnpslpp.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtiedevhuj.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtngvrtyhp.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtdzypditw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtaolijscm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtejmewdek.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtmpubtslt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtxohtpevt.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtxioxyaaq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gthcgdtbzn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtyhknyghj.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtuqfnpxia.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gteecqrvvr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gthsuwnjyj.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gttwjpqtqc.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtbmueovae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjqziyfp.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtvdurkodt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtbdorcbon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtmpakyaly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtfvgrmskd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gthoigzhrt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtzrmkalqt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtuivqthtk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtbukkezfr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtemqrdonj.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtdbtlaxtu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtcpnkojmw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gthqkxktjy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtqfuabayw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtaftnfzst.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtayotvejx.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyhnsbij.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtoxjezzzz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtrygvyozv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrmbfckgj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtfquxwyae.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrhuuarel.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gttllizxti.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtbpfignig.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtvggmohyp.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtdlwymcmk.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtowjpgshq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtsemuwite.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvwzwgeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtxamptlqu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtjvlziusw.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtgktijdyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtxxoybttr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtjqhnkzzi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtukxfvnyi.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gtqcaucxhp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtytdxrjbo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtdwenljkz.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtehlnyyws.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtcmnyirny.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtrhpliweh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtofgavbbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gthejeekri.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtptbmuhdl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtfjjnmgsr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtpzddazyt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtujqezxks.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtbhludrme.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gttapmayqf.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtltrtjqjo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtdhqcjcmw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpaelwht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtoerglgai.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtmkeuggph.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gticknrckr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtrblfcnbj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtbtmgzsur.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtgywglhyk.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtpiidhdtj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtuixhcufg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtegtiaiko.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtluayatzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gttulbbpsp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtttgyvidn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtjpskbcwl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtzzvishso.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtfvqbtbty.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtsxmbzqbs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtjeogyhvz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtvflhljec.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtivvfaftt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gttvwzggej.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtjvizlcgx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtgautmmjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtfxydmzfg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtagveflnh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtyaszgokq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtievatiex.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtuhcqasna.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gthimbkrlt.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gthfqcofqf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtyadgwkjg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtcaijtzba.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gthoqqcnpc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpggfuuz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtzhdyyukm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtsrispvab.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtgefafays.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtjpexgdou.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtmkfwdmsm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtrejdbfin.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtfngienfr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtbfwqgrau.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gthcxmbuzx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcwxhlmbz.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtrmivjsva.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxxjjrnes.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtloqzihxz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtgjbudkjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtkrkxdvbk.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtzwkdsogt.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtpzihqwvv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtbjywhayd.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtczwevipt.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtuuslxdkd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gtzvabsaei.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gttfwdpugo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtdzjarqmv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtmoqrheyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtbgrghori.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtipiauyph.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtdcuuwdzw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gthqnwgpjm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtyohravxt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtvvaxqhrm.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtlgzxlboh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtylsvvhri.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtniwedffv.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtttdtbcfp.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtsbnvnrve.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtegltwads.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtxqtluswc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gthzjamnyh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtjpetcyow.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtszvzqpui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtpjwirohc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtehwzpqrz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtzrszybet.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtmnwnqauu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtzdjoeiwi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtuqycfrze.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtgfkuxyxs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtjmjxcrpg.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gttlmigtii.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnializjo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtuybmxhfm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtkyudeejl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtsedjqlxw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtvrwpjxuz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtzlghgzrw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtjdpmulmn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjkearer.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtvlmxgdum.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtpgckkzix.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtfshhvqyf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtamevvxle.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtsrunkhca.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtwrasdfgs.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtyxbstymx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtbucmeapy.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtbgkmhrmk.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtmcxlpvas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gttbalchcp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtadzyrkyz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtxpzfdxjp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtgkqnpzdt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfgjdami.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtaxyrxejt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtoldhnlls.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtyoptsdkd.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtpogumngi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtvsqzcnkq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtjkwtqitf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gthzezbhwv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtlczfeagt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtphtaskrr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtmzyzeurq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtcjmdibhd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtkrpjumgi.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtwqpbozah.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtsxzteklz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtohgbmmmm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtfsaqdhsf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtpxqanlsy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtxjmaqidm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtlueyglko.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtbjxgsmbc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtcfvnhuzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtfduecgvs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvirefmgg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtgxvdbkqx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtuumojhqh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkcggoefc.html


<!-- 参考信息 -->