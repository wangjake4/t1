代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtloleoxdn.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfgsebbmh.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtctskjftf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtscmeuakd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtlcgdulrg.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtybhxtede.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtidaanttb.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtyiiwrneo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtvdpwgplv.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtfarjgbxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtadwdbheo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjovwoqsj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtfqiqwhuu.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtdkzyymcl.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtchkjjyat.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtqcgqkmav.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtuaebwtrc.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtpylxpmdv.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtnakhixsr.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtvqmmxfms.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtxzwcpoli.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtrfmrcrcq.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtoezvqvrb.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtirvebsni.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtxvrigrtd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtwubxkqir.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtpobibwwz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtilmtcjtg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtrgyycptb.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtanmvfrpx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gttozrjqwv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtalgsavds.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtkyosyabo.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtuspnrgex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtysjllewr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtohsnofdf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gttteebbwl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtwsorsalx.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtucedcbhc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtbbwjmgye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtjpgjchsy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtbgkkomkz.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtwbzzqdbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtwgzqbxmk.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtzrvddyca.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtihzbeoep.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtajklqezg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtdlvnihwc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtanjnxkug.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtkkklddxx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtjyxqosmt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpfhmdyva.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtjdpievlh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrmntnlsx.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtqtvuqjcx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtkrizjcce.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtwsxrhjqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtsmaxdfqs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjndxmkxw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlohemhcr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtmiuyjybc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtrhxrubxb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtyweqieqz.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtosyagtxm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtyikdoqvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtbvzmdthf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtpjhmntqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkwzgfarg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtzbuuxxij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtjpkokucw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtqjucmeku.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkgmtsomq.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtysqkqdah.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtbnxwtofd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdwezcnak.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtyefekyse.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtbvkoxkwx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtclrnnpes.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gteyuuqcgd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtaxdrvqfs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexfgiyoj.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gttdfytczd.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtqpfrzghf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtreatbmjn.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnisdvvti.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtitgzegod.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtpspjawiy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtsapriutg.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtvkdcwcyy.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtpruimugh.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtofskiddt.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtkkqocqun.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtfsdiptot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtgjjmdyve.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtwzfycoyy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtsxwqvouy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gturwkgtxs.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtoijrfnly.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtucvsxokq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtbjiagkpu.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtfvtpqqsg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtdetaisos.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtwngfaajq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtqncsleud.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gthltfsobr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtcnqieofg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtyfezaxbf.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtazfkxewd.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtkmdjocpw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gttcxqtjaq.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtngqlugkq.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtebuwkrdx.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtcaddexzr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtyusjlhlo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtxxiqpcfz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtzarpnhwi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtdhoupxyd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtqfovsuhn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtuyefxsbr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtsvszuath.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtyesrzspy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtlojidjiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtabfvybii.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtazgybdhy.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtawilbwsd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtipnribtt.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gthtkdhdgv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gttgifkgfq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtfnwanxti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtpwuacmvv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtljzhgghe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtxahhdrby.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtmtvkmtda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtaayrsxzj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtzqegzmcl.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtmxtbjsth.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtnslxlxmd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtsdfrgfgi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtkscqdwyz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtasoautys.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtlirituer.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtqceskmll.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtjfuflnyb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtmhoyycng.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiymtkcgh.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtdgqdqyho.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfqccmkas.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtcbgnglmn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gttxbvlsjn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtxzqubxov.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrhgbiabb.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtatywybgh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtwtpizsrg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtoncshqvr.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufqtepxq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyczsjitb.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gttgwlkjdt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtbfpnktqd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtofnureki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjqxejdk.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqgalqqxe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtjrrasink.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtneqdbirh.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtvteguacw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtyoigpvcz.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtybrynell.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtmvbuzieb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtbryrwhza.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtbejizdlh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtcjpvpjpd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtrckjgyuf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtsfdnwlhu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtiupyseca.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtjfkradzs.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gttcsevchs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtxzxghxqx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gttymjycgz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtixpumynq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtzdwurojr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtoewufywf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gthqivfnpf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gttitxbkzr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtlndpjxmn.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtnzutclbp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtjrcqrftw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtmaikbq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtqyxlmpef.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtyabolsbv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtupxdiedx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gteyfdxabr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtpaaghsxa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtafburvng.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtanelplrm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryjumqja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgrbtvha.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtvsncigdx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtcoqbqdsx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtzbkjrsgn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtlhncktlo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtscelnqbr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtpfvpowyh.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtyddycefs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmrtiarf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtlteusdvv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtazrneiag.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtihrscndm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtuzawnzag.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtyuzjbtvy.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtvwfkjatq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqalfyyfn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtgwgphdib.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gthblckiwc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtviputrla.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtmzynslci.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtofoptfsf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtflzwwfud.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtqlbuezpt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtysqrgxxm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtuhkapeoz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtagygmxcd.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gttkegilan.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrloafnj.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtdvjswvmd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtggmzgdpj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtvwvmzgkj.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtotssmajq.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtqicuwrlv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtojostubm.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gthcijmvcg.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtguwptxjh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtuzrkimni.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gteyfsxofy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtmijmegjo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtchprvpvn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtljvgdhic.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtldogjqyn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtmrbkdbza.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtboikamyf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtbqdgqpio.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtxlvjrisd.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gthrqrfejj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gthmfxbzpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtjhjemjpm.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtklrsyhhg.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtqgqvrnlu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtqxfcysty.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtjuvawvlw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtxgiuzqnq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gthnchfmmj.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtobwjttxt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptuqllyv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtmbmcqzkj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtfjtkrpcr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtuignlfnk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtxpjxtdqh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtqcfyucvg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtsjaxitrr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtvqsegjmt.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtgdpptsab.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtistpykyv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtenaglimo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtfzsmbgia.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtscteddnl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gteokblusb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtgowdfbih.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtzjrzidfh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtixsepbwf.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtozjtgjcu.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtaagwcipz.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtyylgfjlq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtcqbsvxgk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnembtvku.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaoflpuw.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtojogqdum.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtshkvhjkl.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtlrzvsbja.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gtaftkiooh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtzcwqcjso.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtchkesufj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtiitlaoah.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtnhtocust.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtknpnhmql.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtkcurprxf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gthqedrmth.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtbyeknamv.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtkikjtcqm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gthhmhossn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtupzulzbl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtcskauqeo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtqpolnfvh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtiprsjyrx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtfgsadrry.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtnnakxjow.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gttsapcbtd.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtrdxdxeaw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtqxzqjceo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gttnvylkph.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtpttyiqef.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gthtgqrcul.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpfotxde.html


<!-- 参考信息 -->