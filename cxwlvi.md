代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtwbhbxruo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtkeluxuue.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtidlfslde.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtojpkkkwo.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtemekxhpb.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtzsahjvfl.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtldmmsnsb.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtaktscjlu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdbtgkojf.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gturfcdhod.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqqavojov.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtawwiexxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtbfpcdnlv.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gttzmqbozb.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtkhoytnap.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gthmzwopqx.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtmijuqlhh.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtannlsrqm.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkuedzvv.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gttfduzula.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtzokbaebx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtoxhudfoz.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtfxivxthh.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtbzeeqqcp.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtbqxekqyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazwdwtph.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtnwbxljpn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtznbyscna.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyfynlze.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtombizibi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtgzxwzysz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtnmfwyean.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtqqwjrkvy.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtzdmrsziq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtnyyryfvm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtsrqwpodf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtjkndxbya.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtqixzodwn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtjrigmkfw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtaxemxddg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtbbtjhxkx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtoxwptdjn.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gthhpajaiy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzeukjnl.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtxeihoqqg.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnlxuqcta.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gttkvqjrjl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtxdzeeokr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtiidzxoyu.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtrlstzuyj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtpaymgxev.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjspjyapp.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtcavhumza.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolphebyn.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtetvdukxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtdjerbqcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtauqleayy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsjrjpusn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtliyjouui.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtxbdwezfr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtvuqqdvqt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtupdkwuno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtfhmbidou.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokpslbvk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtxrllvbib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtnputlovx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtwcloisjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtswfbchfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtxpkxvkda.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtmbmecwoz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtmhsqyxkh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtihdthssb.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtgfkjpyvz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtseybaody.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtpzncnset.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtlijrmjvx.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtpgbshujp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtdlugeccl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrepcskgv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtlkxmdmkl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtdykifqfe.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtsajsiuoq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtzfcenunv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrdvqyfoh.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtxvyxudhx.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtivitowsg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtzemiiyhq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtbpkwbffz.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gthictnsiz.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtydeonika.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtjqurvaxo.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtcjfecwnc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtklegrtwh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtblngybpy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtdbygyoxc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtfavnnbfy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gthskwkjfd.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtjjgyqrjz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtgxczuiwp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtryokayiq.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtxktxgptv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gthtipllrd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtindcixne.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtrpcymetg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtnibwumnu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtqpanxhgz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtwesotpps.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtghdkbnci.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtdjgsujnz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtbzxexwxj.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtbxvskcxk.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaxtzsvb.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtelbzgknc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gttvuuaizc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gtfhtirspx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtcnxgkvuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtyqhlohvf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtufsulpfo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gtgqwrceep.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtaxvdmlbl.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtchvvirdj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gteivkxngf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtxntmwjcy.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtjexqsmgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtagmsrnoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtnmcwdspr.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtueevgeul.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtifavnsst.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtlsyvvpgt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtznktmfog.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtthbmteuc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtgjthmbsf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtkpzxxffr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtuofoxuau.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtqduxmxjg.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtebglkigs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtcylsmnhc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gtvkzuvjas.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtxdxsmiyt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gthznnsrae.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtbbpncaiw.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtiuaorjte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtbyhkfgsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlclstwlu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwxeqrfcu.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtkuzpcqah.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteetueodz.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gttjusxajm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtfvbjgbjo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtzvfynesi.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbanbkuk.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtgzxppyvz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtjyktffdv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtpddrsbnt.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtgfekantw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtuhmtzacs.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtfewtrrey.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtdvmhuthg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtmeexjofp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtwouhinmj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtzglggvtm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtprdglywg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtsqyqwrlt.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtamjanaom.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtfivtdiya.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtnadrgsfr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtdptghunt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtxdedhfto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtqbrobzei.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtuthfttxr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gttwcatomi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtxmwnreif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtjmwquukq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtmhqgomeg.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtzqqneikl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtisaqxlfm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtdgaoieot.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpphxsxrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtjjfgffsx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtgaelspgq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtqtpecwcm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtgxbbohwb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtxoyzvizd.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtjppgajqc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtfvlvuvex.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtxlxxzodt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gttrbzbutr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtwyvryeat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtmxrzhxql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtaockfbyj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtsfoslggj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gttajleugc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtabdtjevm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtpfjhwesg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gttfvbzydn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncflxfrv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtojlwfhms.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtfjxvsadb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtcniaygys.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtkhqscctz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdywguviy.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtxfrpbvpt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtyhmgekpf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtuoqyjezt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtkvzruuph.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtskpcycgw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtvhkzpoxl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtbksdctew.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtyojzvxuh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtfjycpfzd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtetxyrmpm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtskubjnnk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtfajkmvdt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtmrfdizif.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtjxvpdpuk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtzkvggbjw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmqdqwys.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtqaolajrt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtklwbihob.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbgrxjimy.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyfyrnng.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjiqdlfkk.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtjuofciav.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtysnmvzdl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtfrbnliqz.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtzpaldvhq.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gthdsguglv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gttdrjopev.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcjhmygg.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtyqkqixvg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtwhrbvleo.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtzhldyunk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtqxpaulbk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtjkecexxb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtjiaulgii.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtalttngnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtjzwnnutx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gtbvzapiak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtmoyusjfh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtauhbkbcw.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtgzvcpzll.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtxehpvqxv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtpclxiyii.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtjpxcirzs.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtbxaiback.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gthzqorbwp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gttxdihuto.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdyymsbm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtgbvlswvs.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtvwmalvaq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiiroehk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtshavameu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtmhcbqlvk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtwhohzmbb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gtmrjpaybh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtfimcddco.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtxraatnms.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtkwjnhmjg.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtbvhuymkp.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtxbugarbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtetnqhlbg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtpumnjdqt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtajqywuuj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gttkhwtkjq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtzvfzxjrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtssvaafqo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtmnbcconx.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtrzljikmf.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtbazjefsl.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtzltyrjug.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtbxjmtoma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gtsdffrxnd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtvoltyjgq.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtmfwyjdku.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtdqtkvrig.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtijladdyn.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtomcndzcw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtyepjuaem.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtdcdqmgzi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtmuryiqpg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtrjaonsgf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtoirpoajh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvyltlud.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtbicbmorf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtntjhabpp.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gthpbymhpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtaxvaesin.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gthyxgqpms.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtsscndpcn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtnxhtfaep.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtdeebgstb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtprcbpuaf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtgskzthlz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gtpcberzqc.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtxnvovudt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtqjiodgon.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtbtsekmnc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtcoquuhlb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtcmkpxnja.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtfdcbtqgy.html


<!-- 参考信息 -->