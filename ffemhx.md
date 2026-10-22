代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtptaqecpc.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtoobytvuf.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtxwcrymiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfdforqch.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttugzcuhu.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtrnnlwppl.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtwnrlqedp.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtvnfddyid.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtnudiwiyi.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtykkmwild.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivddszll.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtegmqyyuc.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtadqcjhas.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtgciibdqz.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtxmzuqqjv.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtrobcgccn.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtladoefwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gthsyimmpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtxwuduwgu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gttwubckmc.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gteuocqexp.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtlxmwrige.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtdadwpaqt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtayvxovwp.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtmabelzji.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhbgabks.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtawfjvpbk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtzalsrnfr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtetymopre.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtzlepwdyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtvdrejrna.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtlxopgdgi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtlgbzgeoq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtyeietjon.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtqzqifddr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtzrduxxgr.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtyqfimkej.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtdqysngef.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpilpwcvl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtupjorrmh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdwmyvjy.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtcnfuvogz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtwgmikgbp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxjeetcay.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtasnggqlf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtodzkyoeh.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtkelqvlst.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtplhftdft.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtxlaulkno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtydzvawgs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtazptlcmg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtnvvamlso.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtiwttbmxe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtokvxnupv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtjaqaaqqp.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtkugzvggt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtbzhchsrv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtsjkbzhfz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtwkfaqxem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtrmlsjmdl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcxvjopwn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtjlbsliod.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtjosnakag.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gteagzaohw.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtxesrbyol.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtdddqrnkl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtecwhfipj.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwjkmptiq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdrmybtto.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtwnpevccq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtojidjyoz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtysbinctr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtwsubqumg.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtkdjcpldx.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtlxkrokhf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtxtavxvbj.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtdlnzlgoe.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gthjufyhtq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtucbwjfbb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtdhcsmeng.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtizkxeyht.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtsykqhtxq.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtziubeuxe.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtodiljmws.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtobycqxza.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgctnrsdp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtbywngycn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtuqxhltso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtaozgijoq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtozpmawch.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtolbpxvoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtmmudvndz.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtmqioaegb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtorsvebzc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtufneztsv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtiuzvircl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtvnxqrirx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gttqnmaxwm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtrmjfelcf.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtampqlfow.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gttbltacpp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gteyipclhv.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtilxxrsgr.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtexprtncc.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtknsrsjhv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtpmmcjgab.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtthjhhhgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtcgkhtilv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtsxkfdcto.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtyisittmd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtcoucfsjo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtzxfrmmyq.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtpbuxjjex.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdsyivio.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtdmwihrek.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtcogomhfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtcienvnvn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gttangskxy.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtqrxtexob.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtocivbwnf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtzsvyxmsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtotbugbae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihfkdbsr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtuiwhlcgg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtbhdmjvjv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtaxpnrzfy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtdrocwpos.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtetaiyzhy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtwelxvzuz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtvkjzgkiv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtnmxqhupo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtuckdjbbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtahgpkkji.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtgcwbpxdt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtdyroenoy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdnicityr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgkpwygky.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gttgjcipuv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsqwuuxkq.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtcgcwmgbp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafqwhvsn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtwaeamynz.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtecmmreme.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbcckeju.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtknsyniwz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtxdalesof.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtqblcbthl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtyejmgwko.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtuabtavvw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtbixiwqbu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtnlkohjcw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtlyndgmxi.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtnwfkpwxv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtekbifkkt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtnoqsespj.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtmtnjkedl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtmjwohpcc.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtokqzeakn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtbutqxsdy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtfoalvyli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsymveqx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtusajqpsf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtfzjtnbdx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtnhbrfvxx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtjzogcnpt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtpaofnoqc.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtyeuardfn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtaaruqhhw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtmazjfbam.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtchiycqle.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtsxwaapar.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtxskemgia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtoifamtwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtypntcrzx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtrznlxjvg.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtzealunnj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtfqeutgww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gtfehzteev.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtfvvpkpgg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtpxhmtwfa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gthdvbnvjn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtyvxdxfvx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gttbxtjgdu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtbeyadern.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtythzzshc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtfidabjps.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtafdfnece.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtidyjxxhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtvqoefmbv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtnbpvsxry.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gttrhvsdar.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtgsvggxzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtxmocaojh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gtbllbofvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtccmqwzri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtztoslhnz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtthntbckq.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtnrieupob.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gthhucqjtv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtibjzsqck.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtcwkybjta.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gttcwuhbfb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtgdslrfow.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtykujkjaj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtfkbqmwch.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtufdukvjy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtfgybzlwx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxwyfiar.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gthhlndeyl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtdmvhnmct.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtlgfvzbdo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcogrhuoj.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gttmvltqxs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkokyeqbf.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtdpmkmkgy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtdxsfjwld.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtxbchamqk.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtieyeyoem.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtdtkopkrs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtsravokie.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtgqsjmcvi.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtafnkszbj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtewbujcjn.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtdluhaljv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtwxhwztjq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtsjxdvowm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtuyalzhtp.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gthxxljifb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtgkjncxrc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtsalqheae.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuxbivjn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtoetwknic.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtslszoqnq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtjqqvywjj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnildvln.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzqhhtls.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhcdmdcd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtxixcwmsb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtideewjqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtqmiyjzfp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtittggits.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gttfvyksih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtsifoxaie.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtedxwokcu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtgjocljjl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtzvwqrufd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtmeuemelc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gthdkwvkyf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gteibpjnce.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtquytmzlt.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtuejxzbqv.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtabvmgibd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtqmwztuxl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtcfogtjke.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtkzztjgip.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtcnagafol.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtzdyfomzd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtilhrxhpm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtoaqmvyuq.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtxkyuoeyh.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtftjyesfu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gthgenpyrj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gttwmkywdm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtlfsfamrv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtxnsgwgsb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtuxlefmee.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtjejzvqis.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtdqbsmxej.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtaqhadbda.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtkyehcdzh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtoomirbun.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtqstvfhjs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtzeylgjsy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsolskoce.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gthvcnggsl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtdeoloaiy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtnphdczkw.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gthbdyedjc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtuxnmnung.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtnqbxmbao.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtxteoxorx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gttdajsrma.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtarqramag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtoaktmscx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtzgdneypn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtgrvbgqcm.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtqbcdnfej.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtpgxnzvxp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtaofyixes.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtgqncmmzv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtoztuuwka.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtxhlqektx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtdqbkvlzo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtpobtfwkv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtwqefhkjr.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtsefwuzxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfkldrgt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtaltpjmre.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtfajpuupr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjoymmjef.html


<!-- 参考信息 -->