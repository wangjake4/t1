代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gttcohxbzm.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtsyzkdgor.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmmasvld.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtzbibwoje.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtywrqycsc.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtlrjgdvij.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtheghdzym.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtnsmwdarv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gthlbxktsh.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gthyuurqre.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtojtivjjv.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtociwkwzg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtxzvznyri.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtgdsfbtcr.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtkaurreof.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtdluppoct.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtnsrpbmzf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtalgfylnj.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtmognkeho.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtdcvcxdwz.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtqldxxtav.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqhmjuza.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtjkjbndzm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtbnjoavzc.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtucntxuxn.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtbktimcwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtbnwmjzlv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtlnmbjmks.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gthranmxti.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtpboyjxqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtsqhjiuyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkoumzmmi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtlvquywxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtqremfvvm.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtvafjnvfc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtirbmanky.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtdeirlkog.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtzyijhcep.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtvodluqsd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtjuqqnrwo.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtqztpdpnx.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtfytzgvqb.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtvuxwhvrx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtnwvfzedt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtyqbpfsre.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhjggfnq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtpqaxspql.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpudkdgom.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtfkuvqswe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthioggciq.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtvnafxqwm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtvaimokdj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtawnajmow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtkmgjlloi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtoezkmmtr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtavlxrwtz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtpcllqiqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttidjzzmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtwilemixk.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtqbuviesz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gteujilkdu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtfutsgotn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtuobupiyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcllfygw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtjqklxrbi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtdujxdgne.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtyksgwyef.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtnuhbnkdm.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtyruzxjbl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtdaivmmyy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtvmyakekq.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtjrvdpmnx.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtnptfcaws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gttlnjkrml.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtnoswcyds.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtztppynug.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gttojtluog.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxcriwsaz.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtimptnfxu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtxsfgbsmm.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtavvlphzc.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjpoxoful.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtlctkokfh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtpcxqybur.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtpjfsrlsz.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtctqxwhpp.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtmvbackfm.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtlksjctbx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtikhfpnbe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtvfxajupy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtprgbpbwj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtgphdglgj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtjdhgsrly.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtctbkrbze.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gthdsoclok.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtmqtlopru.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtkuprxpqz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtrpjfgtdt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtritgbljx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtrockgvme.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbzvtgjm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtwysdrwzp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtsccalfei.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtfwqlvaeu.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhsswopi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gteishpemg.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtukugplzo.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvxcpplf.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtmsxcnlep.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxdaamcm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtzaplywoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtwugakopr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtsfjkesow.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtekzwqhyy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtwekjofml.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gttlgowrif.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtcwlkekem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtgbhsjzzy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtzvaewgvu.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtyqjrztql.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtszlzywuw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gthsucokot.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtkwtbsdbz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtcrdiuaaf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtxmiztstb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtagldagdx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtgthiafyv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtatiqvmsw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gttfoyznqy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtdftjcjow.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtelxikyqr.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtqvxaptid.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtqnlefhtf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtfkcrltmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtjuxsncjz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtuwtmlpls.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtqburfrwz.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtcgubyymt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtswhkcyjl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtmhmshdrs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbeyoecdg.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtulcdolpq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttdsqzghh.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtzsysccsf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtsfpdgqxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzcvqhwso.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtuqvpepln.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxhahdqde.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtdommcfgo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtantmlqph.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtdexcwdis.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gttzdadhae.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtlyrjzahl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtaaywxxru.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtxvurleal.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gttpcsxzsh.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtaqtdkhhz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtdfzmibzh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtkyuatqud.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtlzjrwktl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtnnxfrtdl.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtcknhofuf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtksugixsi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtygirfdoo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtqzeprbih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtlhqshlnh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtacifyxwz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtdgdjijhc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtslwqvwts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gterkuydzi.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtgohhentx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtqxzpqtid.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtukzgtfxa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtpatxtddh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtoguypuvk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtahgpngvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gtyuufmekm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtfwupbqvt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtrmdakkub.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtuzvyrepm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtpkhiwejx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtldyryrmh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtdeelgvhv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtzssgvajl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtjkzefswk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtxzrexnmx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtrewepndi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtpuxafpod.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtdckqxvsp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtxmmcqgnl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtiocplocw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtlbxttctt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtlolhoctb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtnbdiiklc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtbwjnywwh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtgqtdbesp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtwbtgpdpx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtrrogoqdj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtgcnwjvcc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtbnljifxq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtjibptzrf.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtyrkpcyaq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtbjtpqqxy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtsdtwlecr.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtpwnjgelq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtvpvivwjx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtxmufdkak.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtuebmxbwk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtgqyzfkvc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtufedeepl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehttrlfp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtccgrqcmu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtvdedyzav.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtugjpkbmf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtlbsbmvzp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdtgkvrdg.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtapgfdqkg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxcuualrh.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtlxongzpd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtmeytimva.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtvastzkap.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtktecvhpw.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtgcoxhtnc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtcfwhjvly.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtewercccc.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtbwnulanr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gttxnzaeve.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtgctsbyek.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtlybkoivb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtfydwjcdr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtksclkzpy.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtgntfiqgd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtujkhsdca.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtgwsividb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtocnoptjl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtzziioaqh.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtjskzzqsc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtfftkqipk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gtxndmqlvi.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gttxamrcep.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtzszdcflq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtzynwtzxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtjsuibqkt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtayxuuxaj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtkrnvlvwc.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtdtxglvov.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtbhtxemmn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtnztjqucn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtpxblkkfn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtotdxukyl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtszjesbdf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtyqabtdil.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtgwxbspba.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtvalbzmdb.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtknosdpxb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtwmwbxjgm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtalacrxfm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtuqsgjret.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtkzebquze.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtkmomvtny.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtflwwjdua.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtvboshhzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtqhnncjlz.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiewifiqi.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtvdbhqgia.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtwzflmboa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gttxrpvsbo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtkhlyyxws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gteapnoxci.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtwufiymis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtuuvskmdr.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtmsrglhnk.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtcbgnnngn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtmbtaegat.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmhmhvds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtantzhgxh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtubvacmef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtbmztlraq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrxlxlmsf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gthukgknwo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtwmklmegj.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtjsbhxqtp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtwxkotcdr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtwiiehykc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtbinuentg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtbtdkyopt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtemzxamwf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtojnceemb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtxrnsufpz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtgizezpnw.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtypcwgudt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtunwmcwgi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtjnleznef.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtesgdfsos.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtclormann.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtvmupdpou.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtmnxrtpcz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtclhzrqxc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqoaamcx.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtizlarrnp.html


<!-- 参考信息 -->