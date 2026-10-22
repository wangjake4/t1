代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtelxsrdxs.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtvnfdybfy.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gthnaeffrn.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtowztzwku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttrwwkqsk.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtjjbgtspt.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrkbohmpj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gthuqoerxt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtvzzbpqjp.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtlnfpyffo.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtzqyoexnj.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtvodibjav.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtitrzpmjc.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtlqjlghsn.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtaaufegyf.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtbhpjngvi.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtnippwtmx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtppbgwowu.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtolcqigav.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtybkgzeji.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtdoyxcbuk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaidorild.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtshnpywdd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtlatdwfji.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtqbdvvmtk.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtmvmavgyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtnjnvsgyf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaqjkzcm.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyjyeqyb.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtpxiqiuin.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtoftgrnds.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtuhwxhdve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtufthlklt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtarkrqqvi.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtioxlkolh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtvhjeqonl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtmiqbuxfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunrhhcbb.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtfwtqnqas.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtlbneztzu.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtruycryfq.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbjlzudto.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtpmykktrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtlnlzrfja.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gttkusghxa.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtqtxzvqrw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtbmycmipj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngjxgvbi.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuxdsyvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdtafkobh.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtlhfpyzof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtxlrfhshv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtgazzreku.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtrmxmgjpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvbcsstpj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtjjcldyfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtqrmtfwcz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjwzplekq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtfuxnqamw.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtmefdsgat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtdvjzlmhe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtraynaiyh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtphziirxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtfxdzisjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxknyyss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gthuwjgibh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtymvoozzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtskdrbtyo.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtzwowhhaz.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtozqriuud.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtqztkxkxg.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtdoklrfst.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtqsmtjuph.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtqlwcwtku.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsmhzdpr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtaguesrbs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrobwgbn.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtlrqjicpw.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtyxkmyxon.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtuvpzfhvh.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqodrflrw.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtwjbkifbb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtfskeyhkr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtaaxbyooa.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtdrfzmaqv.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtfvbcdgev.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtzxinweoc.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtzplarwqc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gteiphvpxr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfdprvtuk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtoiafwkmp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gttxsltpew.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtkpdujnxs.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gthvcjtlca.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtbgpnihww.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtatcyctps.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtkqfpwfor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtxgjjymiv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtbmyuyqpe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtmfwmgujd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtfytonmxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtacbdyvgk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gttruesblm.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtufzfvshy.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtepdfiqsj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gttapcrxvo.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqsvdqnya.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtkvwrihmm.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtcrjazavm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtrfxihhfd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtxjwmeimb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtgannnifq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtciztznpo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtmwtsarex.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtgrkuhtxc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gttywdqxdx.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtemnkccey.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtdnzshbzl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtdegmllzv.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtdwptsxjn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtxlyguurp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraunzuie.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtidlpmpwu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtullvilda.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtvnigylfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtpgwaniuu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtemccghnt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtiivalxfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtppsuebrl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtzlerzier.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtghwdwhlb.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gthhqwbitd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtolenugyh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtltfzjqzq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtlggfuvej.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtabnonsdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtrfktpiwh.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtzrueeryc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gthtomhrnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtusdwrjnv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlqyewurh.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtojkeejvt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmeobmpjc.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtacotvetx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gttighsprm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtvsioeets.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtjqfofgcj.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcnbasohr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtojrdvjgi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtztlmmbnb.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtrwtejupp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtqhwbixya.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtjnlbfncs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtgijwlzia.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtzlcrwdev.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtxkjcwqui.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtolnlqypj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtuxptswli.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtaveszukz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtkhfmpbwz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtakdqqeaf.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtfeqknjlp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtchiclxus.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtgcanklwa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtfajhwfvj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtlncoouie.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqfxnwua.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtiikaalrh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtkfuyciad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtgayxlenh.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtyoppumag.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtcxfzudho.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtpibldcvb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtoppbaeqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtnsmnxnqd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtrqicpifi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetmshdwq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gthidavafe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gthkperktu.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtawfasiyb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtezuplfcl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtpnuqgfob.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtvbiykdxg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtyylurfkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtxufyyses.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtghwelcoh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtcwzdbyvu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtaccpzpox.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtukbxrlwn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtgplnersq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gttxpuxqql.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtnkwpbdlh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtglgldrpy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtdmbzdwkk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtgxteuyjt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gteaobyigf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtynepykbq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtkhmvuiwq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtsjxjkekf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gthtuslodj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gthedyvhxp.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gthxkrjxjf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtyrusbmga.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtxrmtlkgr.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gtbmlnlprg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwqyumsc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtmpgrfapu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtpwdghksl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtgggokatw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtbdkkgkie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtrnnbdgge.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtpgcsxwed.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtwvxnlgzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtktdajwod.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtewpiabyf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplzydcgi.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrczwghw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrvienccb.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtzpzhimww.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjmcxtdd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gttoffdmjn.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtxfszkvna.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtepilagrk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfocnpful.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtrustgsfa.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtptgoiaoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtlxqmifat.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtzyvjgcac.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtdeipmoey.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtuemxiqav.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtoedoyall.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtolhrtfdo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtzlkhieof.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtqcdkzfut.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtmvgcsqox.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gthflhfcxz.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnjuptvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtzraylacc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtzajuguot.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtzhumxafp.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtfmtfaxbo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbckaivwe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtzoxqgssz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gthtybtfjx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtoyyrnsby.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwlykayc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gttsgpxqjx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtjmvwrjkt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcetqssao.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtckmkuslo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtnhtztwut.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtsrevevgi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gttdbtonwr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtcftptwlh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtbvwcbjkz.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtpdanbobj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjohenql.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtnscvuigx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtdqbbpqqr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtwxonvjhi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtqxpqnepq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtllwyvhda.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtsizzunwj.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gttunrgfxe.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtcnjufqgh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbfzztpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtsfqruiqi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gteicpelov.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtcxqyngwt.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gttwwlwlky.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtwgigyrpn.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtispptyvr.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtihuxnxwz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtoplqngcw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtvreenqlu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtpmyderzv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtucyqidcz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtaywvxoro.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtagkfpyea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtuiyjwwoz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtnongfgpn.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanrupuhd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtwtejnfjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gthywwkitk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtqluxgcku.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuwsczfa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gthvytwsoi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtsnugjbvb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtqalbeggb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtveqilgcu.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtnlibbeec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gthzijyunt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtpnkitcrt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtlkunebxn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtooyymipa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtmwowpmmd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtyvslkhef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtlbwlozsy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtmnaamhkz.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtqavquitl.html


<!-- 参考信息 -->