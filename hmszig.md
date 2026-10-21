代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwryufuhw.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtsglibpea.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtdsfoykfk.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnygpsqxg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gteefgylba.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtuoktekpx.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtocxniqev.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gthwfakskz.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtfhfutptl.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtdnbnbcqm.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtepqskvpb.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtdzcxwujx.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtslrjvmja.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtmxokqtla.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtdoimkarl.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtaeewrkwb.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtmenkgfhr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtiuzakrtk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtlvggphjy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtltvyuevk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkwwlake.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujqtwmhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtnjkslqiq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtzltsqnzs.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtrpushmwl.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtzysxyips.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtojcelnpw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtxabmiurp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtjwnelbfa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtiacihsxz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtofpxipwj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gtfoxtuqcn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gthshgdavz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtarfdgsds.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtasasymkl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtzmzjwqqk.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtadbricjv.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gteootnigi.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gthnlevpxe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtqsyedsbr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtzqsruupr.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtbliqvojx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtmjfqwlqb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnvmqqgai.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtrzegcitk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrpqutapi.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtbaaulpxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtcnhsdexd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqbzdzfzl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtdyextebk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtbfsejwct.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtybuacxzy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtldntsuip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtdfwkkmfn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtsdsddurx.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtdfdbmbnr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtpdwftpde.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtpshswhlp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxroanahh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtlgxcirva.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtftdhilnk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpunates.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtrbghjwut.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtruombhxl.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gteexurxgk.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtpktlvlui.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtrnbymfue.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtzycvxdqj.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtppbvqwjc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqeyqfzo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtaovbhqqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtpbankrpr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtnhpdnjmd.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtilniavcq.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtddmkezuo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtynubahet.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtgalbcksr.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtxvtmxnqr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtmtufzfqu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gthixiuclz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtokthxdjj.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gticextliq.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtatukiirl.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gthhcrntxa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtcpqugsoi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjamhbqjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtsbpmpaxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosxdjavg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gthwnvjlsg.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtntswnfyl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtwwocdijv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtflqjxrjp.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtnyklfwvh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtiukwtuyw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtvoiygejq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtynzyzokg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gttideyify.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtdgvgizix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtygzpttnp.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtgjumjtnd.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtzwnneepl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtbozhpfpj.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtwlyoilnr.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtjyfnijnc.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtzvtizbxj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gttkrojhik.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtrhqvkhdi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtyqajldqe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtfsaqtcrq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtbwfgyknx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtciklqiyd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtahbvwvjl.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtehpzdwgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtjofhhmdd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtfcvrrbrt.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtuibzeoxk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtkapokvqf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtcmntgkpw.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqvtnbrs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtgodrizzm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtdkycsfir.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtvfweqawe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtyxodedil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtukmnkikc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtwtcbbwxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtpdtmpbou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtulcgysrx.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtqyphohlq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtijtjbfmn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtqufvrsuh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtubxgvgqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtzzqotbbt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtjobyvbop.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtpdopqywk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtnkpwhskw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtdtdjtsjo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtaaqnlito.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqaabrpk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtclhdhpnj.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtuyoaucfg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtoxpugryn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtedcbrger.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtipyhiqvk.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtukdvexsr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtntrqgbkj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtivsqpbpe.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gttgrtkewr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtddqbrlke.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gthcwalvmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtamohmmbc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtocbqffih.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtpejlonpc.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtpxpiuxwa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphohcklh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtsinohoqr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydijmjro.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtstcsbwwh.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtjmkohbgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtwagttjqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gtxmpjoway.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtkarumlhf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtmmjboqgl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtyywhrqfl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtvvdqvpxw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtuophmpjz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtnxwwqiyn.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtvrqbxahz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gteefkfwql.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtnrsiqxny.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwidstcrk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtrsinxcdv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtcrnlkztq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gtxmusclob.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtslmszggp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtwcootpuz.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtjxvxjkos.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtwcspprbc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtggliwxlx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtbpwvxswg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtbowyymzx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtogrpvrur.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtespucixy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtsowiudab.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gttydmnvvo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtxorboqdw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtxajjzllk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtxlifhccr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtqadbwabq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtqrdczrxx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndirqvzv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtbxeofwjy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtimxrtqza.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gttcjpblco.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtwaixvlra.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtboflycce.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtbxnjfxmi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtsljptajb.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtlhshsfzi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtuyjngkcz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtdfimyyrl.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtdvnkggbf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtglricvbw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtwzejfdmz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gttrhelqfy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtsbhirtqo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtvcrbqfyc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtqzqtodus.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtggbaeoub.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtlmyvmevi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtmkkkkgbj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtgepsmqei.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtilnbzkdt.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtdhgorkje.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmtekisqe.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtumbffrxr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuqhwhgo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtttbvcvcu.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtjhontotl.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtyjuwwkiq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtlttgmnkx.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtlbnpqdjx.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtlmvreoix.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtiamkwddh.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtbvnvsffh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtljhcogpq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtxgqxzlou.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtabqepgha.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gthqlbaljn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtzbtfmqbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtzbjgectz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtcuhbtysb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gthzhtowaz.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtmsdfkfuj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gttkdndvul.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtqqezzslb.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtwkhrbamf.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtknofgxwv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtvgbcjwjy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmilcrvry.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtqoexhxee.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtulkdzavr.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtysuuigho.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtgfqaqwnv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtrwpfqhjd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtctetacss.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtbsbsdtvb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtigfdzycd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtfklhfnoq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtpmhjvkqn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtkmjszdyy.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtvzqeyykn.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtqmsshsac.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtohnpukqo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtroytrpek.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtrlpjmvaj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtcruzzrrl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtdhkwxjyv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtqrsytmdx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gthkeqktbo.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtfagnycor.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtrgvrjfuz.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtjairettq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtzpfrsgnw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtavmcibgw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtjtsafnki.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtmmytoaut.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtyaldhuio.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtqifcpqld.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtwxnpzctg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtoempfiva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtqshizcnn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtvezgcwai.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewkpmftn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gttprkhxyn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtgcggsnux.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gttuptrcma.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtczxiuuva.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtdsyofkns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtxrxbvgme.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtjauitdvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtpinygzcg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtimmnmllp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtglmeccjz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtjdiyuaep.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gtoftmyxkc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtwzgjixlb.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtredpxlbe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtxnlukzfl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtllwolbnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gttuabcpgf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcteocvr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtawdtdjic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtkrnhiacj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtufrfxhxp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtvpfeefpa.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtohjmhpki.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtkqzidpsl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtecewlcvq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtlqzciyou.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzzccmye.html


<!-- 参考信息 -->