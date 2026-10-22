代发 wailian999

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgdyelsxm.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gttldgvaxq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtqjnsfjaa.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtlqrgzxbs.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtjrgdjjes.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtwenppzdo.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtnqzpwhhv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbjmuqcym.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtrznjnlvg.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gttwtjqqtx.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtaqppitbw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtfhjpbpld.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtijiayiar.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtxirpjzey.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtxqsnkbhi.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtcmihcqhk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtnvztegzj.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtaakxzpix.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtmuhhhzqn.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtioamtipi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtweifrqth.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtjhwawlcr.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpezhajyl.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtmmklezcp.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtihpbpfhh.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtthvjbdqm.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtpyepgbxy.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeosxfkq.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtevluzioc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtnzpzpqvu.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtbqjxvppi.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtkszgbgbn.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtwxgcnhtx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtshglibqz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiyrmcsy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gthfsvdehs.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtrrpemnmu.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtfeyxkkwl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtplypbgtt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gthbkiplvy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gttqnpibud.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtniicosla.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtjnzfzwci.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtcbkcukrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtmnzymwog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcxdhdpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtdesnpxkm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtmkmwsjom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtikaacxkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtaklpxdmy.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtkbhkynxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtvcnshikv.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtsikbklft.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxedronmf.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtkgxwqhpg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtpipccwbx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtocyuaiig.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtbuczvgkc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtkbdhcqae.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtelztlcwl.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gthlgvyyxo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthliqnbud.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtlpqopfzl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtywjygjog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdoerscut.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtejpbcvei.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtqvacrhxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtavkgcdue.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtlnapmrke.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtykdqznqn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtwgcnkkcn.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmyhmzm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaylacna.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gteutanlyx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtrjelhdzs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtojqqblxa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtlwmmenyt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdcwcawz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtqfalbyof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrgnbhmdl.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtetqvpeaw.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtkpghsnus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtuyzzwitf.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtvzkriwdi.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtbqmegtjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtiutqwegi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gttwegdjug.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtpehnnkjl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtkklhkmwl.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtmeraspeo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtpjbehhpj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtcqedrldy.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtadboouvn.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtzspzxvxr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtggcaxzah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtpfolrgsu.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtbxcohgct.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtjyatyhgx.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtspofzjgn.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gthdaqdxcg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtnhqgpwad.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqssxxfa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtmanzmpay.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrwitclca.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtglzhrndi.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtzhhkunkt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcahmxnn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtktnsqqyl.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtzfwhrarb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtgbihyxck.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gttuojrcbd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtlszvtiho.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtvfevvaqa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtqtnitnbx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtywnqengh.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtwttmvmtb.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtvlshltkf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaqhzmkm.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtvmezylww.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtdrrofpdo.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gthhkldngg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtovihtjlb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtjytbpvjr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtgesyucfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtssziifay.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtqgxskbhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtvxgpglkh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtmuggjtbw.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gthsqprdsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtnrehxpnf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtfijvtbtz.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtdufpceqy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtilypjyyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtmqrtibuo.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtfofvaaft.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtibohafdm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtlhkrovsq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtvtrbrqto.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtduetzguy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuasycbds.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtbnvgrpts.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtslavhroh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtnjozeffb.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtglhehgnh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtimqfeqvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtmhzapvnn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtwbtkjjzm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtidtxkjin.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gthfputnrq.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrtdxczq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtpcxdemqe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtlbheybsg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcpldsbjm.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtrhucuald.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkmhhkoqs.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtrrbpuphg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtnjjlmmid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtshciwsuu.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtqmbznuzq.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtsokwwzbm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtzjoocezd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgxpodwtn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtlebmhptm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtquajjwde.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtfdnbjrll.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtbcfgwemi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtyogiaurh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtryujsltv.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtockrgpik.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtszyslwsn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtaojnvhtk.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtryskqmsa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrwhmcblm.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtnnpobxdo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gtbauzstwd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtmysucmse.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtgpylctyh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gttzqqtdrh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtgfaqguqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtkjspns.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtbgivmqgj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtyktqqsck.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtaoomlzwl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtefpthokt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtjbajwvbe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtrmjjqrjb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtssxqxqtd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtmyrkstkn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwshsqac.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtzylkvzlt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtlqpwoiob.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtvtxezcii.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gteojnzjue.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtukyxrfrg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtjnahuxma.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtnkxtbbec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtuxdauokj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtfltyzbaa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtbvrrnqka.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtnwyvbcmb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtbqknppwy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtwbszzgwy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtpyiarotp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtrxtepxcu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtpiszeovl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtjkfubhzz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gthwexhxji.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtmruixxcq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtaburkrci.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnomuakth.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtljwsxhel.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtimwlxccm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gteaghvzrc.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtnekgjdcb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtasdevvns.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtebbfjqgj.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtwtokklvx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtdpfhnory.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtyibzcnek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtpdnikwye.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtatbdpndq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtujbhheop.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtcqcweywv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gthdzxibvv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtdnpbgfcl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtwmhxzxel.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmhadubl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxkcdbocw.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtlyxpqnrh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpucuiuoa.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtzhpgavwg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbdjqfqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtujwycqah.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtunoyhbss.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gttkvkcubj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtarfhxpfd.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtneiheacl.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtepocahrc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtymualfxi.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtsgucuniy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteroujmoy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtkmhzdwyy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gtwuvwrvmx.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtokgijcls.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtrhxzfvpm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtumsijrwr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyxobsqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtqugqwbde.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtzlgzgbnk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtumqtyirb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtwmywphcu.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtarggfiwf.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtdbhwizyw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtdcofwthn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtggmytkdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtlahkjiak.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtbzenwbrw.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtcrzyoerh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtmznxahhw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtdyrlrhjh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtplsrgfgp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtmelbddci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtpxuerebp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gthnaexqna.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgzljpwo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyifciky.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtpcohxrbb.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gttvsdzigz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtvvkxgpiw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtjsxuocgy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtfmigppml.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtrlyutzto.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtiaevccdi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtwdmxaiiq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gthrvtoesk.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtaeplxgfl.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtvctzrnsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtikkdzbiz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtydxkafch.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtezwfhmjz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtxqkjmgtb.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtribsmbhq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtaczwvczb.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtivmkyzbt.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gttgrpxerr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtrqxoxnop.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtjxksfbjv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlcnedsl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtlqbpjhcn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtrwpwtggn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtczslffih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtvcophohh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtjvdyydjg.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtaimfrjxe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtrriuwwoj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gthppuyzul.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtkedtyrkw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtuyjxeclq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtcyiaggpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtzieqwuwz.html


<!-- 参考信息 -->