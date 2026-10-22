代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtgzbxnmmf.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gteahrbikh.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtxjosvndc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtgfuafpcf.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtugcxvhql.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtwksafoop.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtahnyrfts.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtvqpqyfnj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdwhsyone.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gttgxnfsea.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtcsvqrnzq.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtshyshiut.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtfgeusqtk.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtbmrlfblg.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmgfsdwf.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtynnblhqo.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtzwgbapis.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtejvncuci.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtddxxakso.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtzuwnfbup.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gttnmtfsov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacmsuejh.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtyezrdaig.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtljwkoxec.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtzrfpsyde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtscdbhirv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gtwhkmmuti.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtuhphbzlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtdnhzbadv.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtkkmhxbjb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtkhilwlyr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtvpyxijjq.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtthgymfio.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtwdajofht.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtaimdkbrm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtrczgvqyz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtfnficxdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtidglecmv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtddafgdtw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtqpvpsmzn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtwnbvnqha.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtpafapxqg.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtaobdjyhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtovqkglvp.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtcbnxfdlj.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gthybevwcm.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtpwvxyreb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtqiqkayjs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtqjabnafw.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtrlsuzcpk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtzviuyzsm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzbwceyfl.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtixknqtsh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttxgmrloj.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtsrkfsock.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtytyvaqnq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtsmmcttuz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtxiabpzma.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtxjvnwiec.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtzjxoyqmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlwwqbfb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtuugxeenr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtdixloqcg.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtuywcfhzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtxecpckki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnfjlpnp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtpqjwmlpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtgjcjgqin.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbomeuuvh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtbwiwuavk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtdgwovkqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gthagusfos.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfnxbvue.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gthdigkvmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtplxdtgdq.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtvwmbqsgh.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtlyvddsgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyjqykbcm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtmdnqrqwf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtjuiufcby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtnftphnik.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtngmbyhbl.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtkyevbhij.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtlantpaob.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtenqnnyvn.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtmanqaftq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtjqjxpzvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtxborshan.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtlrpaljif.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtnvxmavua.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtbejkzkie.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtdkebkgbp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtrmefnyyd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gttuwyiroc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtzuaxafgc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtgocgbmjl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtaytwdswm.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtgseidupx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtlxgyvtlv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtzqvpvoti.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtvxnfkjxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtkbfilxza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtsdkwddar.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtvtdpzore.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtssqlcfps.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gttwcjzknm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtmhptuclp.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtubynkkcm.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtnhwvkyjq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtruunghhw.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtqyyxfxsc.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gttwtvwqhr.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtttnufien.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtjykcpzly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtpgkpqmgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtbtszetai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtspydxcnr.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtekmfkclf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gttgmqsifs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtsbqljlvy.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtapnleold.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtvoscysop.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtxksmcozx.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtqktvbfqa.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiqrksah.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtzvxqaoaa.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtnlescqnf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtezgvigmw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtctvpxokl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtlcwaulii.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtcxclldhi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtfynpalcd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtczmlodey.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtjlacrzzs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtoekaszrw.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtafdthjpk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtdruyuzlp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gthdeuuqrd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtfzdrqpga.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtovwnrrwu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzpbsybu.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtkgxvtnqq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtkltqqkly.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtmrzfisgb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtazfhvglj.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtwztqiqkr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzhalppra.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtttcxhvkg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gteomdatki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtsgjfsiza.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbcojyzkz.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtwfrhqexh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtynmwunpi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtajsgvpxj.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvipplrc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtxnsrorye.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtqmncdbfc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtyfwxzykj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtbtpsbjfs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtfvlrdzik.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtznqjprsu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtlujdaphb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gttkpiyupk.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtuzvneoif.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgxkrsei.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gtlhvuiiah.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtrexvvutg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtbwmeszet.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtvariaqyz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gttqphhsmd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtdtrmqcgv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtgybzvtzx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtvxligntr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtccitafhg.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtupviarkp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtemdlmcxv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtkwroviiv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtbawnptew.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtfukokdgg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtxokqpjlz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtqvblcbfn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtuoaegmxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtfpralhxt.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtxahggafx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtifemthin.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkxeugrgh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gttpgmunfr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtozhseqsm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtxusuxnsc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtyrllceoj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtoertlryu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtkordlvek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gteteszwff.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtundzlzjl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtlzaxglcf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtzjquuxlc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtixsujdjf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtdkwboidl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtehkwuawd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtzpqwmpvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtpbgdzday.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtimwqpsjg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtxyyqgdzf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtrxtcjzln.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbminrfr.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtoamjopml.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtimragfvz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gteywfwetf.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtnrfpehvs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtxxfolomr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtjwzsqjzu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtpfbyqicm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtihinekxk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtgtlfmziq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gteqormzqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtxmbuxodb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gthviqqthx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtbgnqqdwj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gthorwcoks.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuuenjwma.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtowbbszoe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlzspqzxv.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtmvdbubrz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtrtbqjtay.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtksdabviv.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtdjawifqo.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtzhtblllw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gttyqmwulr.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gtzgkqqrix.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtvbypvxfj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtpjhcrpvj.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtixfzqkld.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtwhbwrelo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtabreqmbj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtirjadvaf.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtzekwokyc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtexulmrlv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtatqmxram.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtesgusekm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtxdoliuxa.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtnjmlzhtu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtrncxwusp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtqzbpfjvy.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtolqoqslr.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtsyyzvngp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtrjdfzzsd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtpwdokvtd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtokzwaskl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtsanzikqc.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoglgtiyv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtuqjfiivz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtedmytdyt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtengakeee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtondljegg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gtfqlzuvwi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtjpyrrjnn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtwiulehti.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtmmyyqtus.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtyzffibat.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtyljoquft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtwaetpymp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtpwncxenw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtbbklylaa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtretdtkyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtuksxnquh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtrxjsgtqu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtobabiokr.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtgqxkwqph.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtnogpudoh.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtiiagompx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtiwyumgvq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylbfxnmu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtxqtoftcc.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtaweiieaj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtfclnxuwq.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtijwwyiay.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtrzcvxclf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkyqrfwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gteqgrgjgx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtrjkannzl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtypogetke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtihjdfomh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtxzhosjlq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtmlyhfoyv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtxrvhukex.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtxmlfllza.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtuveelcpe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtuwwkgljh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtzsvuouyu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtkfgxpqle.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyffbhweh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtymccfbsc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtdjkrwgha.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtsssdwlyo.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtotznduik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtrsuwgleq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpknhfxtd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtqydesdmh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtswbsggkr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtpwofpiaf.html


<!-- 参考信息 -->