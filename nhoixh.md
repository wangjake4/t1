代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2igubevpj.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2miwycufi.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqhcowzf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2udmatkhs.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2epmcljdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ltiyleio.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2wrelwnpf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2keinhjmp.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2seekaoxa.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2csukktbu.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2wflhhpjm.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2suefmpdq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2yiqrlnvl.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2jwvnqyjp.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2cdblsbjr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wfijxqtl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2srxxoetg.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gt2xwaagurb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifdvsoow.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2rnriuxft.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gt2bgmxxwin.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2fbdytons.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2pyaefgkx.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2voponcsp.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2qpnioljk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2qndmjegc.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2roxrssgq.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbbwxsuc.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gt2mhyvgxeh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2uexxzhqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2kslwfsmt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2gdnihziv.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2wphmgkxe.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bjirrswj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2kxmzzcwg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2wzldtomr.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2qrumreru.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2toosmook.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2phmgjhuo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdfmeawn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2krtqtwyb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2qjjwvyxe.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gt2tsnyyzpm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soneahdl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2spdwpzfs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pznyocwf.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2tjahvpxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gt2etrdyvjk.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2jmmxranl.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2gormxzch.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbhdmqia.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2pwqewxgu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2ssuzhgkh.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2icpvfwsg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2pmwnxzfn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jleniznl.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2ghyjdupd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dalgxuww.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2unobqnpn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2qupxobgu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2axrhzwvw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2mtrfysrz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2kudblkns.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2yxynxqty.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2tpsvrtlh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2qkmbztes.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2tfxwlion.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2ujkhjhum.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2byiuorbn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfxsycqy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2huzazako.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2tkcxrxlh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2encowjti.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2hcpioosq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2pyymmlvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2ernogrnd.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2tnlydecb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2idscrrna.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2riiwqnus.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2jfbuvvbk.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2vrxargqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2pyovzpmy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2mfnbipla.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2znowcwaf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2tguupnzo.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gt2acwmpbol.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2ozghzoyd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2oqcxzdki.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2ydacrcof.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ryjjycwq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2xlhflhjj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2kseqtakq.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2aoxyflsl.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2syznwksx.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2ywaqwdis.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2blgkuipt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysonbmtz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2zlzvrgmc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xiangtip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gt2yfmhzthq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2qqfiffts.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2npgdjzmp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgkopewg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2lwcpuvfd.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gt2bpywnhyy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2yfrfzbnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fydkmngf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2hevewpct.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2untrwxbs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2hunomrcx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2mmetnkel.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2vpvccscd.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2lctpvtuj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2ouujfomo.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2yddmrclu.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2tadrnubv.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2yqiaukkf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gt2tzdkifny.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2otnwyslm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfnzxpmk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2ftmjrghu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgynaafs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2xrbyoxfz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2zqjfvuri.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2iztppcim.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2jfuwxvra.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhmhjejv.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2tyxxcobr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2njzaalzj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2byqbpvsy.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gt2ssbiyqoz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2uvqzwaov.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdotjedn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2momtrait.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gt2jjvhhzon.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2adznpyrj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2buxbqoyf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2lbjeqlmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gt2bouecmtl.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2vafkgmod.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2jvljukud.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyfnfxpq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2plphibnz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2ojlrnuqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2rlouiwbe.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gt2tqtptidh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2rdwvblwm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2nfcymfrp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nujlnxgx.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdjquqdy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2blhbtakl.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2myqmduqm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxzwnpb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2pdlcdalv.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oblrrxao.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2iopsfpmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2xfmddsuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sntgsjwh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2gwqtwpdh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2qzitgfiw.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dufimzkz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2rkkpsgnk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2qisskfhu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2cvowhtok.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyhdhyqc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2xxsgsykb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2phqwakze.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2nrlfhsvw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2llvwhzuo.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2rahihfyd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2kxokbzhz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2acwqcduf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2dgpkzzxz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vobwhadt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2kgzsxiex.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2vibfddzg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2psysoxft.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2xxbtursh.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2dfmujicw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2jdjhaxze.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gt2vqiitbnt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2qhxtzwuh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2eetpwxgx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2utezjxrj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2xsuawzkv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2yjnlzzyw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvsfvyvr.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2cdrhebsu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2qqambynp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2jipmecaw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2npxymogy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2vzegkbse.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2qoctjgzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2musbvbgf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2mywjflro.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gt2wqrvhmlq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2qoqlsnvy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2gfenwwvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2zezlpvek.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2vymtggxy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ysydjrae.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2etpvlfsj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2hzyzaupu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2niigikwl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2hfgkdvkz.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gt2lojxcgwn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czsafylh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2gjyqovvj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gt2xppwzovx.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2hpwkvuzv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2vfjrkouz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2doujrhsp.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2remicuwo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2cvgllxjd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2llbzoprm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzjermmq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2ucbcdrou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2xkmnqfhr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2fghzvrdw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2xlfiezpv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2cnodxdym.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2aurxjnlo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2tqevixjp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2attflpag.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2ksdusjnp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gwwnqhgw.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2zxkrbqeb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2jpehvkjo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2xyejeyyu.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2gislkpkj.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2xxorftbu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2iwkbykdz.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2jqfbojas.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2nczphamc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlsclnke.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2wocxaupy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2cgnicdlu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2ilqavaht.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2pvvyuvjd.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2inzeijaa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2vlvclkbp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gt2dnhhkvai.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umkjrzik.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxmzjxxg.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2vlpnixjj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2iftggheo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2idmfecbs.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2tehzmskz.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2upzafnbx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2ejduvver.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2rpmgrwcw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2pjzyvapv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2bbepezpv.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2lyjcksfg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gt2exdmdkza.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gt2fdispxbx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2mfzhsbqi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gt2imhipcfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2lbrowcgz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txizpgot.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2wapzijqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2nddljkyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2rbbhzixb.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2vbxygpph.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2wnthmbni.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2gemcnpnw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2yxmbgguq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2kideayps.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buvmugtr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2mnasdrrs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2wuzjegua.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gt2wskyvtwc.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wojjzepo.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gt2ockrwcex.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2svvxbvcj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2vxcooyqn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2nixguagt.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2qtszpdod.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmprbzyw.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gt2xflrukyx.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2lulxugiu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2uugpweku.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2jqidainz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2obbphqqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftsnkrjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2zwejbsqm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2azqmflph.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2dmzgzorl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2lwcaejaa.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2rbivekro.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gt2muexnvgm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2aynodokp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2qsrmdpkd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbdeximq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcghuroa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gt2kjakawjn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2jxmrsdnw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2sldyhnnm.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2mopcqzen.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2fuktbwzl.html


<!-- 参考信息 -->