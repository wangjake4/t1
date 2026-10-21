代发 wailian999

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtwrktihzz.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtzelvwxpy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtrlgzmvlv.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtqhvfgqsp.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gttiecaeak.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejqzkyaz.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gthigpshme.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtnifwktkv.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtysdaxfqt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvzwinxmr.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtzikhmytn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtcvuqgdmt.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtydmdlyqn.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtghyvsshx.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhujqgac.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtjvlvqoes.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtqxmcmlui.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtquujxmyi.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gttvllfrlh.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtezrhhwlg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtiolfqrhf.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtqqqkplrw.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtfyyfiffc.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtscyhkylf.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtutsvtpsa.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtmyheugfl.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtxwkhdyyw.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtnkfyppyi.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtatasgbzb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtzkihsqok.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtcglpfmjc.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtmzsglzqr.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtcixykuek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtdfeuyqpa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtgmmgfgwt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtypyrqygk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtwcowmccr.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtenqvtera.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtkvpdkceu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtymbzegnu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtmutwmbtg.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtrcbfhhpd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtfulbzynd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzcsldfp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtzlxqxnam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gthgqgrafl.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtnateajln.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtfjuulrei.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtmohfleyp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtajjtnigk.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtbkpogpaf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtykvugagc.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtdymxfarb.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmvnraji.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvvnhxrvr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtuawvbqgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtnrblctcl.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtlozhknff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuvnudrq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaqvgjoci.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtmnatgrcq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthqntpjvt.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtdlnrbonx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtygvwjbez.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhwohbhr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtupdwnqyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtyjlstxgu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmkbmzes.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtvqumvava.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgceoguxl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtwexmwoub.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtodcqcxmm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtlyltmdju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtuvznblum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtadkpzlai.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtmwlncwcs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtbarolxnd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtxuxzyvev.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtccwtkzjl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtnkixpdrs.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtmddnagev.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpuhtkvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtxsbwgroq.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtlnilzbac.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtgxaeshsh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtnhuepwsi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtldzndvwa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtyvlasiab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtyzfxmzbm.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gtiuczxjpj.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtesmwpnat.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtsurxjwxx.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtezzdqknh.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtmzixicpk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpxwpaojo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtykufwfhb.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gthjwgyjkt.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtqjinwoyb.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtkrbrazux.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtbxcyfwss.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtlstbqzfs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqxrdoeqa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtwlwersrm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtffajwaqp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtbkmniwgt.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtwinmtaid.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gttxfumded.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtemutlyrm.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtrzbecftf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtpsbehbag.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtlgqqxmoe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtwatwtlwm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtjxygotei.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtxwiwksti.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtgslmskxk.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtqmmxhkzo.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtzcjatvzd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtmtizkiod.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtocpmdtai.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtmadckeva.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtzppkajvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtqrprnuot.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtpgwdiyft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtsgpiysyb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthoymjuzm.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtebfkknfp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtlaedzxiy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtymqwavld.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gttwlnxgez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtgihyrxxi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtigaxftpo.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtgqexohku.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtqtrfrirp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtshrvhezx.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtbpgimtas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyokpsjs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtnpgoojon.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gterdihovx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gthykfrmhh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtfltefhvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtpsvohuej.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtwqtyybua.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtwucdcexl.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtqcvgkrjs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gttsalqzke.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gteiguhexp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtzoecphrf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtfqhydpsi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtvjzmhapp.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyjscdgm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtgugpwgbe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvhxmvrbs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvkpuczov.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtgmrkkoer.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoryarmyn.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtnhytuucn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtcgbryccf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtmivsvoxl.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvusepabl.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtqrzbjyuu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaeasioo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxdsnejsy.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtsmyiqqzk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtjxntdfze.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtidqldwbk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtaxeoxxbe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtomjscspi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtbhnojlqn.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtaommdmsk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gthbfdinyu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtecptaqbq.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtfvqwggwo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtghvoylha.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gthbrxpneh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvfpmyqd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtrvjremkq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtblepqubh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtnamzixtu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtemwnjtqg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtqermgwmy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtnfpihhvz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtqgwggazo.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtuizjvlvv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqexasgx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtflcvliev.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtctqrnawl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtndtuivuy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtwpotwytz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtzglskqkf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtlwgoxfcw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtsiwaouwx.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtdfdzfzti.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtoluiiate.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtlqgdwxiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtxnxxjfuv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtytohwblr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntoqiaqn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtjqsizsqb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtvfndhnos.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtlwlegkcy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtzhxhxaie.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtlywgscfh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtxzjkgkja.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtyqdgofyv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtdiqnmbya.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtfwoeliwx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtbsicmhwj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtnpkvwhzy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtmsbccvpr.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtofamscnl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtkwpqnyee.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtmorzqkad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtwadbomrp.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtdvyxyhgm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtjdeuhvjv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtdvulvjkl.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtrxegcvnz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtcrqvnqsy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtekytxdsj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtzzflawmn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtyloauijh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtsrcjwmeg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gttgqflwaa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtihjslhlc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtgihpegei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtfhsfvrtx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtfdwtgslg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtayfhtued.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtwyatpisy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjardfgi.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkvbmypr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtwkzxywhk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtgsgkaplx.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtjmgzrbdw.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtyruzotwk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtpuqyhbdq.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgzlrwqd.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtqbvujemv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtkcndcxcv.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtaydzhyvn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtlzcbwrfk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtxlahnkig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtdfjgsuns.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtrykmbqkt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtukbygovh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtcdqvxewk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtmsrphyoi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtdjvyhmoo.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtyjcraizm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstaagkxd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gtzlfbyfsp.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtszmukbty.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtgiyxdefp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtavmyipyx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtwdxckxka.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtwhieukfg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtnwngnfib.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtbfnkjwwo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtbcyepwxu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtprztfalr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtpnaojwlq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtblpowsvr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtxwuaacqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gteukoyace.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtlevaazxw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtwigrkmwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtcgfaupty.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtjwatekrq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtcanzavlr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtyfxofmtq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtzxcynlad.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtzfzgzmgx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtohthvgdb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtlxzeljgi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtnyzpxjor.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtdizaszqp.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtgsmprcep.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gtsabiaasq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtxeowimud.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtkpsjjnlj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtnzllqjpv.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtdhukykev.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtgospvyxk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtauamfomq.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtxvcifntw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtxqtcbtoh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtenmdnsqj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gthfrhmohm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyunibxmx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtzoacgwtd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzhfdrhbs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtegcqtrwm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtigcuenst.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtalughjrz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtnjlxuccd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtloivlkwy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtwbdrohki.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtvdmswfpo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtvwtujujm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gthgnytrsb.html


<!-- 参考信息 -->