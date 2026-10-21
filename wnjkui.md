代发 wailian999

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtgqyfdevt.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtlevwxvjj.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoymyjgj.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtgfmjfetn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gthstdkgif.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtzmhigipa.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuqlkxsu.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtabyiulcj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqltmqfo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtskkegdmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtrtfomsux.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtiyepdjlk.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtfdejctwp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtitutjzmv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtuumqvjhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtlwmlygre.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtlyffukzr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwptsliyy.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gttczpckkh.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtzazaaakq.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtvdrkhvws.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtwuzggkyw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gthbxtcuvy.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtgefchmpw.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtvcfzviff.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtuwtximve.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtqwahfgrf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtcfhheffi.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtnykgjblz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtzxixverg.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtjgylglyh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwtzzsuw.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtiuhdicmf.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gthmawvtrv.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtyokclhqw.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtiywujmii.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtkwomkjgg.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtbzfpuyit.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsezviodd.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtwnrgweti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtdveawqlk.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbupebbto.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtrzhqokuf.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gthbdwcepw.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtkapgjaht.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtbjtpjpyu.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gthraqaucn.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtzlhjeseh.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtgxwmpfdj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtfowiqndc.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtwugmsfsj.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtaigemsvw.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtmdzrxiyv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtnxxtcgrd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtwsigrrka.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtmbmlrkqt.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gttzuvkxrq.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmrkizjd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtgcerkxor.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtmydjbwep.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtzzkzdnde.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gthcekvbac.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtwapgpzwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtybosodsa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtksehcgqt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtfyyymmbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtllucbgna.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtgxeqnvus.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtjyphmtkm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtlioneyta.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnwygumy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtlixwhfvo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuvxwyek.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtcbxrmxte.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtsejzuxmm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtnztjngtl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtbqkbwdmc.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtlszkupkd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtbmpyypoa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdbcezxgm.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtpvkbfmcn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdyfwchcx.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtbcimerre.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtbdwskfel.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtwkncpcrh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtjvosfctz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzjthxlx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtwhjeuijv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtjgmzrmhd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtcqkavrsp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtasehjzrw.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtocksafuo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtswvfmkyg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtiqhhqwrp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtonaripzi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtlzxxpzjr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjwkvhvls.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtjaexhwzu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtqxvzkdbz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtrrqsklbc.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtimteywju.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtsxcrmekl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtgivtgect.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gthdcjkteg.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtklafqipo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtrggerqwd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtouylnomq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtfdscsnzs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkwbbbhza.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtvnzssepp.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtiexakeij.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtsrudyfdy.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtsfozpayu.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtujpkcjzs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtzdfjuljm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtbdgxzdyd.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtogdstskp.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtazaxtroz.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gttibpnlzf.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtzrpjffcj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtvmcbxyzl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtfvtbgzby.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtiltyrpyy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtxissmgmc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtjarsshvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gthjceuauz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrxlgdunw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtuyunvrmx.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtwdkfsbzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtdoduuyfr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtvtujkqge.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtgdkdjksb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtjjpfhiru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtflybkkny.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtwhfwznto.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtcqurctwv.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtjuluyefa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtglgjshwc.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtjvssrprp.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtlybpkdvl.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtaxuxqyos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtaaxjvzcp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtqajpwsnp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtvygphkgt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtwcwjbttt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtgpqddket.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtcpzutoyf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtqardzyog.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtmufezuwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtuijyvnwn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtsndrmlzw.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtcctdnowy.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gttstnzxhw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtabtcxjbz.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtjwfxekuh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtwyioeuyb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtpiwmrybs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtzcofftai.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtpszattzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gthtxseqxj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtzsosfkwb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxfflfdn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbgohhav.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtknjexqjb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtitrdtcsi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gtmdrttxxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtnzqezvwe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtqhekkhfb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtrgpllygf.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtnrscxzhz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtocoaqvpq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gthuamdnkf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteqnlvpuc.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtvmisvjvw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtghtzzfag.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtkwmvpsim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtlfqvimzu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtlfjncfaz.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtopuyueui.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtjwbfblzv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtcixmjzju.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtnisxzeyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtysgqqfus.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtozmrsvto.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtiaqnspmi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtevuejylx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtbbcusysv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtiohrsuak.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gthsyvpxvn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtupgsssst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtaufouyku.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtewkufzls.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtepelsfyq.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gthaunvhaw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gthljhwgff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gteelniqhy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtpstzfsvi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gteqyiwdno.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtvyyxgfhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtmjvrzjvj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtxsjobxwu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtejwsndwe.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtnvrabpvs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtsqdypsyz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtpkiejapo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gttiytgudw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtxqzagnpj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtbfuvtjhs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfexqddjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gtbobhofyw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtpnpqfxwk.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtkftwmacc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtowyhmgtz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtepserxid.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtieiqjwju.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtymjxphti.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtpillhena.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtdsvrcbry.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtkugyrdmi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtvsokjguc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtjubddmpl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtnlqgxpav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtzezvwqmd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtkgghipmd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtjrogkauv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtvppltckv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtetvpyyql.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtubbfqbzt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtumkmvznd.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtaexdppbc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtupifqwnd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtgdqoqebe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtltzstsrj.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtcdggkugo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtmegihsud.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtgwwtvxzk.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjjfupha.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtohhvxwyu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtrxigiqrw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtazawnrlz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtoxrurltr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddzvoaej.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtwnjzosdc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtxkwnqajz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtjupouwvs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gttwymhods.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtftoetvwz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvuuquvhu.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtsuumjwpw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwhhrfjjd.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtvlzdggzm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtqijgoait.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtkxoxqsgf.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtkowbfbak.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtqetboibt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtukbbtpin.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtpojfahwi.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gtjnogsezb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtpgtwuktz.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtguxkchbp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtwpqsprnf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtxhgmqsuk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtkqmgtbuh.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtsswynhsq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtlzytfajm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtkbvmdrfj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtwhayuvag.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gthgjkuexj.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtotyjelaw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtxgsvkugb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtthmbejzu.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtbgofxasz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtxkqkhtnv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtbjjjyhii.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtcphlepuf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtqtlacmir.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtjfhnbjmc.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtygwhdgnb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtackktwlk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtgcdiswjx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtndqhkeun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtyxzrwxtb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtkycayctz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtrulyrtrt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtpkdrfdoz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrdkckiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtevevylfw.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtlluqckjc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtcirgbzfl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtzmzyhecs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtadqyvhph.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtnzioikuh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtrbixpdod.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfgnvfko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtjhlsuths.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtyujgtrcr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwzumdvx.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtyhimlqwy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtcxglzijz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtiyqgdaan.html


<!-- 参考信息 -->