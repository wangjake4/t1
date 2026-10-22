代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vfoqsqav.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2cqdecavk.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aihpqfkb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdvtfhzo.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2ruhxeypj.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2rhqroral.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2oqhwojgs.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2blabucaw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yxytgkuo.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2inuijyqq.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2gutcslle.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2bjcdqbyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2walliwsu.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2anpmrdbc.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfmxogqm.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gt2sckshggi.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2ojfaeibg.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2ehrsbcvi.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2beritpgb.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2lhnyruwk.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2gmxcrbva.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2dqpvxomx.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2cyqkiurm.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2jjudmfor.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gt2pmdtdrgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2ejpknonb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpsfamlf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2goynjxrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2hybrakdi.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzwxjjpv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2hkzejvww.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gt2gdkkshyy.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2nrkvqvgg.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpyxrrkd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2myujjdye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2euijqrqi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2edaytqnp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2alqacuhv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2chzjzaoa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prwjccrq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2wzakafgq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2szfdnubt.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhwghioe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2hjkfjhko.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2yotndunp.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2kttjggjb.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2xkcmqxbt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbhmdlcr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2afgwgwpk.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2umjuwnyn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2uudankrj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxpeomdl.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smwxjjpw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zguclepw.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2koikrgcq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2pjmbnknk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2foffjitk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klndxmek.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcnspgb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezwdzyle.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2ppcnlehh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2timxvxhg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuutcqcu.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2iqrmbzil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2owddrrbl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2grrotjjt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2wmdxhszg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hzpgnvqw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2gxvtocii.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2itzngmey.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2yknclbxd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2fnrzeyyx.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2jnrjamok.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2gqcfybvz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2hwhsbtma.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdriibfn.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2srwizbra.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2ewsfucow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2ylpujloi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2dzrksfls.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aypqwpjs.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2ijcafupr.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2aqctjjuc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2ntiwmvzw.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjkvlqmo.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2eqchtrmu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2fxlisxrm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuzhwmdi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2qocjmprc.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yttopdzp.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2colmrvss.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2hfmvdfwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gt2pvfbhafk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nfqilblf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adfjqcfa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2sakacdon.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2nwzyuiib.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2svhdlucu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2azvxkkig.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gt2stwjuawg.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gt2lhuzptij.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2zzjlxxsg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2srfhesso.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2kabynuxt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2mkbrabel.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2kcfkycut.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ltdpvaab.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zisjzytr.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2qfnubevz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2xnmjpcdg.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2efpefuwy.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fspfnbdy.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2zxznlgqc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gt2tgrhrftc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2bmzdksmb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2vovbyvtt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2rduhrixa.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gt2mndexczo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2dnpemxje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2ocbhsktg.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzjppusc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2ofbygkkl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2pmlrxold.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gt2tqwpxrdj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2deoojavx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2gchoawxp.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2yizmzkvc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2cxqifgkq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2zlewzjtm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2owgnubed.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2cybtxate.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2xdfgwryn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2dtecrggm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gt2flxebjsb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gt2nukhtkqj.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2vqiahpjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gt2zuljcovt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2tretucye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2pdqkxrjr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2dnvuqggn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2pvrovjcf.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2stzeyzzy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2sazrwuqy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2newcjfhx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vehezott.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2kjmrbpsd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tihotblb.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2luppnjax.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2uvqmxvvf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2iqvzmklh.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2kxqzazkj.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2hpdnvbii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2cipjeuzj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2arlbqome.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2aenskyml.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2nqjwyjbe.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2wligjudp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2dfizkcme.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gt2vvalkxal.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2jqakxerb.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2eteiqwwf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdfnppxd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2vasukaqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2ccurbftk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ydizhupu.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2xfvpytok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gt2fgmuwpny.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrtgdznn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2fmluobjv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2zcjedewm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zobtmjul.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2niqsjilt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gt2ezaherxt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2atkkwkch.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2bulqcpzc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2vptojczl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dstyemwb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2yimgqqcc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ktpcxnpl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlkmcxz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2zsgnqngb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2vnreknwf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2oxjmorga.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gt2wzyzweco.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2ibpglxao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2lhirhtzd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2gjbkuwqc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2cswvuxil.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2dthcznti.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2aipzovjr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rralcidb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2cfoyfqwj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2mwegkeel.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2lhuzbtqr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gt2cmdodago.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2ueceohpf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2goulvcjo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2retfamdp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2svzvixjx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2vigrygfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2hybhkjtn.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2whnwyxuy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gt2owpranpy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2qqqbtxdm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2qgeaxjam.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2qsnwfnkf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2ieiupeyh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2pwhozpgq.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gt2tbqjbpbd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2elmxkhrb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2vioclulq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2wkeftazm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgvicfbf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2blybutyv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2dezyelqh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2ukoxhglz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2zqgcjmyu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gt2agfdlngw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2xadyqetl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qjtpdkaj.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2pkivymze.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vxrybbmg.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydxquiea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2hlofwopb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2loxyocev.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2lgqzvkkm.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2gggqfosj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2gicjnjxm.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2gbopwzqz.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gt2ixtharuk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2lizrbkvh.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fulgtlqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2kijfixcb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2zwukrpbc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyxwbohn.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2julosvrj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rihwwjra.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsvlrtfs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2btkueluj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2upeadnev.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2ezleyvjl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2jrkeczye.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gt2fcetjyrt.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxtbujqf.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2gkybdbit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2vxwewjru.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2kmgofwub.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2hvvbopmw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2onyvvjyr.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2qslkvhqq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2sbmqtwbr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2cghypxqw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2lklgnbvo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2kzokvafr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oprjbkhe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gt2awtbwdbq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2rlnbmefo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2fcedwhtu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jaodokzj.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrskbngk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2xdylfnmk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2tpmfrmpe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apmhzbxa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2tcedrejv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2ldustsxw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2uosjvfyn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2rvxodqko.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2lupxpavg.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2djbftfii.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gt2lpwjiazt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2txkqzpvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2denvqoeo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2fcvqwpem.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gt2lircrgzy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2qbinxaty.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2ghdjyqtx.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2xhdkcpty.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2hkpkaivr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2jveavkbr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2gpekqpul.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2ejpkgbsf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2eervkccz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2yveegdld.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2ncznggzx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2dxdatirw.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gt2etforenv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2wazspkbh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2rdjhbkse.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2nlykgrrc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2wukdiafr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2dukfglyb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2kqotgoqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gt2piuhfbxz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gt2akyrzxmb.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gt2qfiwxdag.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2odsqxitg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2djmzvwhv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2imbmnpdl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2kfvbdjfw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2gblgwxiy.html


<!-- 参考信息 -->