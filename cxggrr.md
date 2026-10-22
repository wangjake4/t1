代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xqybqqqd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bpfgbndd.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2vauoklup.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2bomrhiij.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2ccyowxyq.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrxsgcsm.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wttlahue.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2dvqokvqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2gncvrumn.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lmszndhy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2cvdvlpvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mlxxkdbu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcvbxkts.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2suobjwsp.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2jfloivdx.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2zaihxiim.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gt2dnppiell.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2zntvexxk.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2phavzlfz.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2korjvmfs.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2fiapsgxj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2jeunquev.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2ynbrqzjk.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2cunqzbkd.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gt2uxtudhxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2ouafglcf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gt2ysukihut.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2uarafpls.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gt2kkyqzcsd.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gt2adauxpme.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2sienoonr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gt2zalgbzxt.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2dtvswmgl.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2suygpvfu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2dltoqedp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nteoickv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2iyvohudc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2kcoxlyqr.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2ekvznlzd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2ypqnhnvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2apeobewp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vknbhlrn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2easadyge.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2mfyaaleq.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2pzjuqvyq.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2vdvmepjk.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2bonecfge.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2xgravnsm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzfxukfy.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdjxousv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2bcshfgbz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xxvaffdc.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2xutlyyij.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bptfdtuc.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2epufsell.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2ixxjmgca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2mrwyusdo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tobzcmay.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2uwzkukci.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2ysivjoil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hybovdqv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2bxgggsin.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2wuxgcimd.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2csqffyqu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2xskoxwev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azbfudit.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2fajncsto.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2bzjppiek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2panqibvx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gt2vspaoinc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2ezflsgck.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpoqzkys.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2kffnsdeg.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gt2rapwcahe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2vyrounkq.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2rmielgld.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnaexrrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ulbtiuxh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlojnmdk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gt2xsomukdo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2kombskoh.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrbggwvm.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2bqoaztyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2huikaycm.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbwrukce.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojddxhed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2tmimxkyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2bsjvelnd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2mfmpujgg.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gt2rxvcipuo.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2plvevokn.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2urwgkrki.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2orrozybk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2oagopwgg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2aafsrdwl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wazrwvza.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2olhdtfvw.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2grneiywc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2fmduykxu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2fjgvdmfa.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2fivyedwe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2yxctxtvz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2tqkdyrdj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2zpannnor.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gt2yqwlvanv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gt2vxvfvmjr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2txzhxgfb.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwlpqugz.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2tdvrqslp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2gysgtwuw.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfdnidkh.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2ilvimfkm.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2kgrcucvt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2fipnwrch.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2wlyuestk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2dozlfvyw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2nnpkvsyz.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2vhdsqwec.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gt2roojmtfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gt2xmlqpvli.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gt2oobtmuka.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gt2rnylmdka.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2qdkdjuli.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpvmgckc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2kzxnumim.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2xesdczyk.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gt2etuijplv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2gewmuoeu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gt2xeqwonro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gt2lugvqknp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gt2aolxzruk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kbvnpugc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2ijbjcxpr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2funinlhl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2jqqjdkze.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2qxbnzkij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2rshknljm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gt2foapdetm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2kfmyptud.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2pylkwaid.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2rubtepjt.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2epirtlxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2bwigzqom.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2qpxlzaqa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xbfbwatp.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2obbjrnbw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ecjnepcz.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2qhlzkdpg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2jaimwtlm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2wnbvjqxr.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2gmoegfaz.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdceyywn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2qojdysbf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2twmhlnmq.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2blbrgbiw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2xmebmeuy.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2jukgtnxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2jbixvxbm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2ipzdcwju.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2mhbzkjwo.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2xdakqnxp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2oaoauigg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnnmxdow.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2fehwydow.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2xgszdjuw.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2dffbkfpz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2ubtoopbn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gt2karjcouo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2fwdldbtr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gt2wpbezztm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2rlhxfirw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2ogfakert.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmbxidir.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gt2lhrrjabb.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2nnefvsdp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2myxwtvtg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2oahzklgj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2emjmbpdy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2rmrcypvu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2fucbfxpy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khwlwuiz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2ngqzpzjm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2joqmlymz.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2gwcmbtqr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2rlakgnxr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2qonvehyd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2nnwkgenb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2qdzxzkip.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2hodazryg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2knbxnyae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2dmyfgumc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gt2wbeoptga.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntmtobil.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2qvlivzbu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2oktllqcf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2tjggkrcr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2shwypmqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxzbvwoe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2oimmiwzf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2alntttox.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2ulqwrhdg.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2iojuaoud.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2pjzxruck.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2qenvnyna.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2fbfhovxh.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2yweaueqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gt2qnirljcs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2hrpinvnh.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmloxcnm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2kekudilf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2pynnwnuz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2tkgvznqr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2zodwqjbi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2semhhsjk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2wgtwwlyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2izchxpcf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2otwzewao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2cjbsqhkl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2sbdjpyjx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2cfqlmpnl.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gt2upmrghyz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dujgpomy.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2ewdkufcy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gt2einitkyf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2yjjyyatu.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2niqfetod.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2laqgobvn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2gpddhtgm.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gt2evipvshb.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2bsitrdez.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gt2golyuqsr.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2lexnzezd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2demkjwdx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2mdehtcko.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2ijgiqdxv.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2dirjqort.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2bvzqwffv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2fsctbelc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2mquzaelh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2mmxpsfmh.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2kvspihck.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gt2pwgkzwkj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gt2snidmxal.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2kcapobcf.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2cmsesldr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2xtbqwzlm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2zyxgnpxx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgltzmrg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuhlwmsw.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2jggkzmca.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urkmdhpv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2mwcabadv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2qruwhnww.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2inwrgdlh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2fxpcotet.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2hyfhoqjj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2ypvtawnx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2owqivkle.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2grpnzdzv.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2zbdpmydj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2zytvkzkz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2zvjltiiy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezqqfncz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2dkaxdefd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2natmzbed.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gt2wxqophya.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2vzaowjrs.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2bystlemo.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2fmwvhpvv.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2zuyljybr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2iunbgspk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2xebstdgt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2sesxkpby.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gt2fvvjeltj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpogserv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2icukhtal.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2hhpoltyk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2yfwidgbq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byobmqcy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2lijezzvq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2azntswnm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2jclplggw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2cfsiszfm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2oezopqws.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2isabykhj.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2rkdivvdj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2zzluwqbs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2ofbexlci.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2gvnihnoi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gt2pwmmbkvc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gt2gwjfyukq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmzoavyc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2spqlqcav.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2lirwxgpd.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tigcdfrx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqvmlbud.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eefevqtv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggmbzica.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2yszzpkcd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gt2xeogaopg.html


<!-- 参考信息 -->