代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtpjawvweo.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtesongwck.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlluiozje.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtdhcegvcz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtuyhvlwcx.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtaguxtfdu.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtkjhinpht.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtchhbmnji.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtgvavotmo.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtejuwgbgw.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtjguyeojb.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtrbwfiahz.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtmchqtpeq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtdamdnveg.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtyqveytbb.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtqqkzsksr.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtkbpdwvzs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtkovnbbqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gteoqgpotc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtwvugixau.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtulrevkez.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtkhmrehga.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtnrmkkjvk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtakzjjiaw.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqttwubso.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkirgtpo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoawfqgmi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtpgoepbqx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtqxfmcouv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtszahjoiw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtumqsehcm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gthbklcxmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtgchpfxso.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtskqwfqlt.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftshtkvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtmkvntqic.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtzubxva.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxgrgvcrt.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtdgnkgzha.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtconyfsif.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtbyxontkp.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtsvvamvyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtbvpcdivk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzedpreix.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtqaizvdve.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthillfbav.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtipmjgaoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gteivoqelo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gthbmxgtjp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnsnzmsnn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtlgplngtk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtfiporazh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gtxogrzxal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtttghozfy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtnjwcguaf.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtupgikovg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtyulootzi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtrdffpwlj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtovrdnclr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtmzbqgxzk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtgodcurel.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtgnmwoyze.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtrzbagnqr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkoxoaorv.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksmhthxs.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtkjpjfvxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtwievzpau.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtsppnsain.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlsqcviv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtlvfftqaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtuwacexzp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtzpvvilzv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtjcdqsutd.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gthxspzobc.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtlnfjfsof.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtqwytacji.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtcgoamgrr.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gthiikzymw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtzeqikeyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorxiaifi.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gttvmadkdo.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtazsrzddp.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtixvcvjzg.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtkfblsjvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtbyqrdzya.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtydprjjox.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gteyjddchz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtajqlgahi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvggiaorq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtygupmqlw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtktvnzruq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtbkabxzpx.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtepphcwpq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkhywyh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtmklpksgq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtxyaufqoj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtvukzbzgo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gteoketczd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtgeytzjis.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtmuvjmxyq.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtopmbpiuq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtehbnlwlc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtincvxcxl.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtqbzdpuav.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtyrrjwkpn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtfvbbkdrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtrohvzptn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtvxjyrwsr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gttroihgvp.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtbuqqifpw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtxfahvser.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtcqxlmlpl.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtpprklmbt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtdwlzpolf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtolqgunbj.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtjmzfaqkw.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtionmtccc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtpzacifba.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtbwmzgzlv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtkwlyutko.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtjcgvzmiv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtreucgyoa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtnftdtwai.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiblageuk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtxahoxsik.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtvaadidnl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtpscbnlcz.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtorwpzwmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtojvxrttv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtjowhtyyb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gturtuwwuj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtzehpklnw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtvjfvftkv.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtsfoklfvn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gtuwkywcpu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtzqegwkkn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjlgklwui.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gthsmximes.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtywheeena.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtihdaodwv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtlhcmqvuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtqzmrmnpw.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtylnkxfhb.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtmhjqgidb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gttyoqkqao.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtwkdjrkee.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtkquuburz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtmgtrdpgb.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtrefxdvyj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gthmrpzbbi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtlruyezzu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtchvpjswq.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtndtvvswv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtpedcnzdz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtxuiyksxs.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtzdlkisla.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqzfsquyg.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtomypfeus.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtkejjimhv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtdcbkdkpq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtpjqcbikt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtlogyrmwy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gteqtsmkoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtbddfcvbw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtzmmircnd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtfhacnham.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtqhsbvbea.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtejzyzfib.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtoehujfjq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtvxbhizju.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtsbadobdh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtfntoyewl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtrqllnzej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gteqxjwvqd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gttdpbwgdh.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtqdpgdnli.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtltpjxprp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtmnkysagp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtbucbdspf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtzpsqrfpr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtbjpyixvx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtmwaygdul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtzjefwmir.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gteovbihlt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtxntgwyvm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtjiztqbno.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtxfnbfoys.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtzhhudtcl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtynsbyrzi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtcdcpwcec.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtwfabjcey.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gthfjzzspt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtbpnczkcw.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtzrhyreht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtihkvfsze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtbttrvphv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtcopopiuj.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtduqokjcg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtthtghxlo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtarihvpdc.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtlfknpsla.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtwmqekdio.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtoatgupbw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtthwsvgdy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtiojjpfla.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtvremdauy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtosseumca.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtpgqvdxze.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtxofxlkyn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtwjqmvmem.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtdmxrivbp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbslryqvk.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtcwrxtsgf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzmchjyii.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtkgccwvet.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtzhjhqntd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtqtexqcib.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtovgyetmr.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gteuysyikq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtantjzzcr.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtzlkogfks.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtpdmnxsov.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtmrcddaec.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtdelttbuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtabrncykn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtpekwrtek.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtmitmvprk.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gttdzsraqj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtebvawnoi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtoaguobzs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtzgjlpwee.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtnzdxoesm.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtlypaviqe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtyzocpmuq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtmpwiqquo.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtefzfwcfg.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtvbnltwby.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtqeotejgn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtvkvrogej.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtkxvtbbqq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtqgmqkpkt.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtbxbiqamd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtoznkapwj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtrrmfduxa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gtfbemwybp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gttfofhfuo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtkyovzzud.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtctguohad.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtlmijeffc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtekhfhrux.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtrpzzkwim.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtcjxgupvf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtvczigvwx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtzkiauafw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtfbomqszj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtsdrjjsfu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gthjrizhtj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtglfzyzsv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtwnrlxzwu.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtgozotawm.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gthpkctrco.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gticttziic.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtvasbvwrh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtolpxtomv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtqcvsexng.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtvzatrmvm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtypvvqhwm.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtknyiteju.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtflfpyanr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtuaefllag.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtrbnoketz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtkyxkeriy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtkczowpel.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtjabbmady.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqngleou.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtjfihvdar.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtxbfovcag.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtyvvbypug.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpxdqfho.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtfybajvnk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtwlgktxgz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaapnxphv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtgubjtqxc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtkyaduckx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtseanhjgt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtwbojeedb.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtehkradog.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtwzsagnap.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtgnusktmj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gteprqgbqj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gthoqfbghp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gttogavnit.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gtepaxwodd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gttnojnwtt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtrmhaiaee.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtwphbcrtf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtwbbagzlw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtdyxxnhun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtywqdbtgf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtzenvqpnl.html


<!-- 参考信息 -->