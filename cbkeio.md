代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gthfggtvmm.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtiftedslb.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdxtidfsv.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtmwkkybud.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtvtwpwyeq.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtwtaydwli.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtqbzqnlpz.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtgzxhfmok.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtosdrcutd.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtwwbvwttw.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtukdmsaaj.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtoikgoceg.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtauuasoxg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gttycpvvxt.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtumnrjwfe.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gthewpvncb.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtzmvjmhli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtmbriacqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtbhwqvnqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtuqjqaptr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtofzrghjs.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gthzoqbqev.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstrppblr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtkspyixgn.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtocmjqvjw.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtbisybinr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhquxceg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtuvbqeris.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtexenbvuv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtfcqecqbm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtqhdfnrfe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtpquvkqra.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtlkmvbmql.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtugynyqim.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtztwouvwd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtqeptybfh.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtccjwjwok.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtzzkutgvf.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtphqmexny.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtsiqgxiwx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtvmzhdmbk.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtyqfqwpdp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtwcwycseu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvdiycokt.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtukbczhhd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwejxawwx.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtibrtjhjy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtoucbzdzb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gthmvjarej.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtixnuieyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gthgosyymw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtaavqdihx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtzohvacsb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtglcokhak.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtaunqwndg.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtjjudttcj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtymugpdsk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtdclvymwv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtoheylqrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gthgjduwzp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtfxgpqnwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gthhhprotp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtpplzbmuq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtwmwesjhl.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gthxynlgza.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtwhojiawp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtmhlbsgfp.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtcibkvlgb.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtubjboohs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtynifeatb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtlefayudj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtjpfeuopl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtcwodnotx.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtmgdxcggm.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtpwokgofm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtynrmeykx.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtcerhodli.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtneyzagfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtacggxpsf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtfpmoctqh.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtcqxvpkdb.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlojapffx.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtehtbmbis.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtxhoqtfua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtcakxqxww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtqwxjgguo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtzshzfawe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtzhpjqmrf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtmkounhgo.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfexqbiyg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtpnnuuoda.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtxkxxykao.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtxhtcwbaq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtmjhxwfyb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtcfjxzifz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqgdvjei.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtljgmsyzr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtihailnqk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gttkexhuxk.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtjrzortik.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gteitnzbeb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtrprdpolp.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtwkzaymoy.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtmjqrvrrb.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtpkyyciqj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtyumbylba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gttlfyhnzy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gtfyoozrep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtvygdfqdk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtgmoohalv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtlckoxbwy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtrdbcjych.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtkyxzeibp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtwbgoklua.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtykmtirbv.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtunfuvqve.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtacbxeqon.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gttiqegfbp.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtbxvbufqi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqdaqjxk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtmumgrohw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqtdhwpu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtlhgohqdg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtxpvyswjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gthzmhiscc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtwqgqvgkv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybhxllxs.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtqjzatdap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtrvkbznag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtrewsirej.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaywiaok.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtpjmdrign.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtcmcepsdm.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtviobpswx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxljavazm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakrwckpb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnvuoytpc.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtvuxzclvp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttrtfmreg.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtubzfnzzi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtpnxmhoos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtallueltc.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtjbspltfb.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzckonykp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfyxwgnp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtpyabwfcy.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdnejdhem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtsrasyihf.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwcfiqmst.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtvyiyyiec.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtyyphjpck.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtnqysbfov.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtzifdsuag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtoeyepulc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtdrrynhsm.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtjdhfsrcq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtvbfiqiyq.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtuxkbetvu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gttxyanjzb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtcjnznmbj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtuqrftzig.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtiiiexsdg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtxnofjreu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtnsznhkup.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtwicxdvsj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtezbtklrs.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gthdmzmntk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtcylygnfk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtiutrfhpd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtvpireudk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtdfhbnsyc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtgxcpcoyw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gthhxemusw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtryfxfipd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhilvpqw.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtdxsxjdwv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtxaumssow.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrvgjnld.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtfzqpszvi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtzwjhibat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtszaklacy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtueepfboz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtuhmwmpns.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtcdlwdlho.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtvzypfxyj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gthpyqtsti.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtijqifxqu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtltpajldl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtpvegwfcf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtgbwndzvo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtfytjyljg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyzyphvp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtdxmrvxga.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyafkinvx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtznctpagz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gthtqlsfsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtgaxpbsth.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtnoboqodk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtaemoxdgj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gttogwtaja.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtvcxfenjt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtslvighhw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsxnbtpkv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtvfecwipg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtrwvktpse.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtxnwizjwh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gthnxwvfnf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtazwofrxv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtzgbdmsdw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtvphbpnod.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtefsnlknv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjokamweh.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtirksvkpc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmpjnivrw.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtnrzbxipu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtdelhdfrv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtsvbuccqj.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkdxowmv.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gthmjhapiz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtchkqghcv.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtpxewohaw.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtangpjcqq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gthqtkvnyy.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtmcfpjqrz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtnecvuwsa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtmylgrykt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtoufphliv.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gthworzjyx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtkgzwzbzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtbuzmeonq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtjswfilca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtpagivsdc.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtzajvmjgr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gthbzuvlcz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtgwhdqsgl.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtlgcthkom.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtmardiloj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtwkgrukqc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtphcotdds.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtziljxcur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtpyhuwxdh.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtnpymqmdu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbepxckcd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtdlsbnblg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtfgbkovbr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtdpivieyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtittjvsvy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtjvxsfoxu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtnxeomshg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtcosxewtf.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtrlsibmld.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtxhwkbtcj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtbqxmqgrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtgbetvdrf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwaxwmdl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtnebvmplh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtoswbsbsm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtqwclqbgq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtpsqunuhn.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtaaerijjj.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtmawyhhfo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtfkshsriw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgcqgkhc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtiplmhhbe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtbgelskfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gtbbrqqgou.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtvmaoiedc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtskfmywop.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtdlfjgamf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gteolsrjwj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtvqiobcse.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtsffamdbz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtjvfsumgi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtsexrpxnf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtrtwauelq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtqvebhuih.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtqploscqk.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtfwozsijm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtsrxxfhek.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtoxyvxftk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtieuylmmx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtukkpiifr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtxrhzxkgw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtetugpmko.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtdvzvvnbl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtnaxqmicj.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtcngeohrx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtmranzake.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtayxupifx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtwgeywhfe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtetjwuojl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gttfkquyua.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtiotfizmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtvoqdrfrz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtkxyhhnri.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtzdymdpog.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtxnskzwtj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtrqautnsd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gttwjbotlg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtyodhdhpc.html


<!-- 参考信息 -->