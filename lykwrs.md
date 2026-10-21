代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkfexqlad.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfnvpfic.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtjicjpdrs.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtpweityol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gttwbysvel.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtvjfjksuz.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtcimouotx.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjuboocsx.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtgymzhfqq.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwwyfouf.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtwvpssdzi.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtnkfwjvux.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtafotcspq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtdcakflsk.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtzvjirflz.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gttzydyixd.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gthihqobeu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtdygftjft.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtkhnhkamt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtsdlhcpnw.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtonqszuad.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtnexrtlit.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtisswllfq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gttniamvjm.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtgfntrrqg.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtihlwtbef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtcwwisdqh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtmcykjcmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtiwoeohlc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtroqpvgpk.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtsbxdwqqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtkpyvctki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtksmzzvpk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtyieopdhh.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtddstpgzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtrgpqoqic.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtyrnelwcg.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtyfctutau.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtdteigmlw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtavgnnmqz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtkoyzfwwj.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtytqbainh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtcwxcmuum.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzvugzsbl.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtjacukfae.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtztjncjfk.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwapqup.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtnsivhhmd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtetqosvvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtvjjgatjm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnplwgqkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtpxpfelwm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnhodnrg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtqmwtsukm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtqayyhiry.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtaxkbszrg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtdbddyntz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gttndtoega.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtgloxnrdr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtstwcbsco.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gteacpuhdw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtfvfxqzya.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtypbxdwzm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtjpeippxv.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtmcwzbxzz.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtcgevlmbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtwbhgghlh.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtmfbtijvz.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtacwpqwwa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtksivnwoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtjasgqmrt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtfccgykhb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtimvcwkte.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtmrkibpst.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtxjwbizjb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtycpnhxbu.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtnxwsnsrb.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtpogtgzrb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtinpgoqns.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtzjbhvjqm.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gttvimascs.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gturewjsxv.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gttetqalau.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmmlgafg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtcfuqbvca.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtyaysorph.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtemmldjyz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtuablywwg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtxihwfdcf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtrxlrxcxc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtunujdrwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtswspdhlm.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtdewyganu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtwrstxkeo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtyfioaean.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtgiuwvpzf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtvfkgzfhf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gttinzcejh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjqkarbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtarjuoomk.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtrsjjcegh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtnmmvlwbz.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtucrbwnaq.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtryedmzou.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtzotrbtef.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtzdcsfxje.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gttoxboufj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtnakqrpxf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtqjrpurxh.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtmevhxpkb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtimnvjfak.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtcjefqoag.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtpdlvjtsn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtfcfxomkd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtdhhgnxjx.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtnuiuuyme.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtomfhsbjg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtxddeztdf.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gttlwznlvr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdyrbzki.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtivuumrqk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtfrggkwcl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtweucmvjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtgcgnawwi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtqthvpkbp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtdhqxxydz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtchvjklmm.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtvrpixulx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtonmoydfz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtzjrhiauf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtsphdrlwe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtdhxxtuse.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtfkwsgtxs.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtivbgmnwi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gtdootxvok.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtctimmkit.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtddwpggkt.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gtpywgucpq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwsllgide.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtpvpxzfgx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtskhaqvcs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtdmwjedvg.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtfknmttmw.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtbcpcrtox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtkkkmtphz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtmwpzhdeq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxrahwud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtnwndxssd.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtxvteeatb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtkedmtdpb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtshmvtsmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gtjhsewcxe.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtfpmjvpqz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtnndewjyi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgfntcfx.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtebrgbeuj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtbfywagmh.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtzwsnrvsl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gtgurfhrmm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtkjsmlpjk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtbjwpihuv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtyraghgfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtezwuiykw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtfzuwmdtz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtwtqesfxe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtnezdkeog.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtgsanqu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtlnreohbb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtmedaundy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtuqliyolp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtsoayscjf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtvhfnzxct.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtngvcubdb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtgcwgaahf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtvtcebdrg.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtuyedrjih.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtwumkkqvp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtloqortcb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtturrfiox.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtphbogfbn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtqgkwaqrl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtbooelqha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtdpwmaugw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtcmhrenzz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtduppgkox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtmnlufqcl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtwcmhfatu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtftxdtvnp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gttileoisk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtwmjlxuru.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gturrguhdi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtwowidrdn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtyyinwoew.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtbndbhctw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtmehghqxx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtytufxwet.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gttzppmnky.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtvyniumbv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtxvirwwll.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtfckqcacg.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gttebsgftf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtebinrzyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtlpkwaqfj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtnbflwtbs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtwmguesre.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtqyuftghh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtyhuavvcm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtfkjksreu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtudyliiwg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtynapwgom.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtdtydrlnn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdgbikwji.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtcntejqhf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpiohbfto.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtuiemqexn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtfhlhbtzi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtifelwkid.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtodynjhrq.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtpfwjxdsd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtitwvqqsk.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtdifbjzuz.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtidbjwzsy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtxlbmdnhb.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtlnctvvjj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtxlownjmr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoqgbjwc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtrnakordu.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtzrsmrqbi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtmzikbycs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtpmnxmmtr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtnqniabyg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gttxhonvop.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtmvoxflei.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtofuidzmo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccakfqif.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtsifwefdm.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtdyctjgzb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtiwweczxh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtyxhwrunc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtyodvuoxd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtfbtxhant.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtrsrsmiep.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gttfnnokag.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtgzhfwutx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtymjripgx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtjhtoeavq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtsnskorcl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtrjmtlztd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjotznni.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtvzxfdvmo.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtoyyrgami.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtjtbttxxa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtxexyrvvu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtiqydumuf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtpwcntlyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtswsnlriz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtbfpmqeld.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtcyjsgyzs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtpynwwkbq.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtcikpifyk.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtybuqrkbl.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtjcbxyfpr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gterzdmrhj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtoqalrdjn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtaweuxpkd.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtdjvbowve.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtkznzubae.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtxoljvkcl.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtinysqrrr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtoccmdchg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtensirmvp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtbnmxoibx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtstvujpkn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtybxojoet.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtymqnwvmj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtceywpsma.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gttjgdihze.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gthlimyfpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtdgdbjnal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtgjvgcvny.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtyfzwnmvy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtqkwcyvxq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtfkvusspd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtbuugofuj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtpujmiirz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtkzvqcxlx.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtepictsql.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtfqatgvpq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtgpjvdwsq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtzczjlerr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtwhwzzgax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtdlcoijbk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtfopjdqoe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtywizwqgl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtfxlvynyp.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtxsognlan.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtpcbdenpv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtmmmxwnoa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkgyjwiu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtmxguyniw.html


<!-- 参考信息 -->