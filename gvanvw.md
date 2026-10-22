代发 wailian999

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2ruqirpdi.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2fkrbqxlf.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gt2yenbekue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2pbpvqpof.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2eoyyrita.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pximgoit.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gt2nhkvtexi.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2fpguwmwm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2nwtbsbmd.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gt2angftzfh.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ljcbmcah.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2rouxqyzz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gt2xltsyagt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2imsdlfuf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2glgfmrcx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2vayvoihn.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2jfbuuliy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2mkoipwxe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2rfgvmjvt.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2gwgwapjk.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gt2zenvpqwu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2pxdvjeew.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2lmslvypt.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2uihytsdc.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2zadeudam.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2qnxijeux.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2fsuhfpid.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2pnkcluzp.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2ccoohdtv.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2whvfravm.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2pmvafhza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xjdcvwmn.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2cfuhjzlw.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2tklzdxni.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2rysefezh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2isiyqzxi.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2sotinjeb.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gt2yodqlkya.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2asvnzqdq.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2wkijvnle.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2vwlojjrm.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ibnznwya.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2irusieth.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2uzorhxlj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2qeipwpwh.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2zsedpiuo.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2qudzpcyg.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlhjcywe.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gt2ozeedzcy.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2jvlvjzrr.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owxpwqan.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2lxbgikxh.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2orssgled.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2rbbqotob.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2vovutirs.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2unqlawej.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2byxtctcg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2glwvlsxs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2purakawn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gt2lttrcglj.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2wkraijhi.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2mnwjcvqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2ojkoxqyp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2bewhxoko.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2clinquit.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2mdmvgnun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gt2odjbwabs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2avcowftl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2awsbekqz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2bqlimulj.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2qycdsxbg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2krrbdfog.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2efoustow.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2unddxely.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gt2gxnzjezv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gt2ucnrliif.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aekyqwtz.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2mllphpoe.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2qyqvyrrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2xlnbatvj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2bvfdohkg.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gt2gvwdpcnv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2vqyzpvyu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2uogrnxyw.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2xnfdxhuz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bzsxhtxp.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2htrxaslx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2jcpkjroe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ykqokqkk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2pkwoqlbn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2wwcrcfwl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2kkuzhnuh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyhddwjk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2fzqtuvqu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vduicmvz.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvsgtltc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2psjqogpf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2eudfysby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2palfklkw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2rmudtzwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxotfxqk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2pslreakp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2yvroadyu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2vyakqlls.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dscczdpg.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gt2odjrrwpq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2wwnzmhdh.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2txwmqoqa.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2zfhafqvs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2xamoqfqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2kggivomd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2gybgyxcc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2degxabah.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gt2nrltnpiq.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gt2hqpblebo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2alsosmvz.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2vqmxhoff.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2sxrjiszd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2uthcryso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gt2wotihiop.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2issvlllv.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gt2jkkrutcm.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2labisohl.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gt2ponncmbx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gt2qjewwkxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2hlruvukq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2ngnnhdbx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htsxtpxt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2libonnti.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2bqefoycz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2wwtossgg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gt2pxsorlce.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2bbziwuec.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjslwfch.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2vguniiyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2cznruhfc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2izchsqkg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdicxrjf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2qsmlbplg.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gt2viwycjol.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2dyjtnnrn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2jeqpohkc.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2wctfvvmv.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2igyhnaag.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2hozgsnqo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2ubpjeorc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2ybldxmgw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2bsweltez.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2uqmtqdzm.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gt2uqezbwxt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2qdttyrtk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gt2hgnnenev.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gt2hmzqgust.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2dzbameuv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2ebgyvlax.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gt2yurtekhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gt2bzncaziz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkrbxyla.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jefioiig.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2zupyascp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2dngabflv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2qpowuiop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2soyjzpve.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsuokumi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2yuysfiqy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gt2vqlakxwb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgjqjecu.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gt2akskgpnt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2kbqcstjo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2hxwbqvvj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2wlndptjg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2dtcnjwgz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2cbsynoqv.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2nnpgryhi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2atzfiiet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2nuwwcihv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jtvjvdjw.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2okiyeftb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fhgkpdhe.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwiewbei.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2kkzewhtt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2rrrfkpqz.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2cvlrfktn.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2zwxoidjf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2ufvemuwp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2majfqbja.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksjwbran.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2fzqknity.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2uofwyqqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2bbxlaxvc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gt2sntfwblo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gt2dlyiasks.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2dxmrjgqr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2ffzwuwhq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cebvqkca.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2cpfjoqvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2kweojljr.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhbnhzqk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvvshvyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2bskcvity.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2osrgxiol.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2zvfxyoza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2fxdmarxo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2matqhhss.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gt2xhafduax.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2cqsswohr.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2qckottns.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2lxjgidto.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2zrbvrpfa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2dmysngyf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2ejmkyjwt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2ckbrgglx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2olcpwezi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2rcbeztmf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2qghdpbae.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2atmbbquk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2wujchkmw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2zoikzftk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2hueizlbf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2ukaeqlul.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gt2ytoxoqda.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2jzpffawi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2fkyboqzj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2wmcvrrvq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2picxzwgs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2uuvfoylt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2whnkfdrd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2webmkcgl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2olmhmwrs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2ihpvbeds.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gt2edlvgqrb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2jfwajpiq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2ppfziizc.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2hrefourf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2qfsjrtxo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2awgjzbpo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2ebarvevp.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2oktjacbd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2vjwyavmw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gt2xtmqvqjk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvfixnlr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gt2zawbizie.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gt2gzforaog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yutwmgga.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2gqyornek.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2coqumlpr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2buhfundf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2xwgoolvn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2vsscvryl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2hohjgqvb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2zvwdtbzb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2afrkgtog.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdjhperp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvreoffw.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2okfstdsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2zwcxszxb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2sbqmhqry.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2wxyhxbav.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2dihospin.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdfxfror.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gt2opvqcoyd.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2kgpqcfuz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2efmabjnv.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2bmzgbljr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2jfotqnly.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2ozeqevdp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2nwtdlvgv.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gt2wnxxkaev.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2aufvhjez.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2wlwsebjc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbfquptb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2ofpnaiup.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2gliyduky.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2scrxmzay.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctzvxjbg.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gocfijck.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlranxhe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2uoihtqos.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2oxlezupt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ezcbkblk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2zkskaejn.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgzykbcz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gt2srpqpnqd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gt2pbsqpifk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2obmcxuyd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2wdtjlxxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2ofzrtuol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2dyrzdodl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqgdhttz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2cfstcqqp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gt2yxampmif.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2zxgbqcvs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2tkltjujn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2jyfryddu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2fdyyuoez.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2ybnfoisn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2wnjybfbm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gt2qrsdfkwq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2gbpleoys.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vamimaor.html


<!-- 参考信息 -->