代发 wailian999

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2xtmepryv.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2gjwucbsw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gt2dfuotwpg.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2cprkwqyo.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2imssymip.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbwscnvs.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gt2dkqbyvxp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2zcqmppnv.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2wgzssjff.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2slfpclyw.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2dtlgeobc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2reigaemp.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2labovwhv.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2skefojaw.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2cwqxwpbf.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2tgiwzivu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bxpsaelc.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xhqhmjil.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2slipplbi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rmjohvek.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2mbyyytgs.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2bowjdhel.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2povxuwvy.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2fjbqbdak.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2qtzlkttu.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2karqyoqm.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2alhqfdwk.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2jhllmyrx.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2cmuzuwiu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gt2npoytewh.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2pupxjmey.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwxmlrzv.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gt2weadgrpz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gt2jwzevuvo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2mpiaewpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2soyqsqht.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gt2sgszfvue.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gt2xtiiqcyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2ncxzvfny.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gt2jwqkcmvg.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2ozdmblnv.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2cqhibajh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2ukjercti.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gt2pcepvuqo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gt2ajeldalm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ekghouvq.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2bmbigtsg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2nywmspfx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gt2oymoxsgv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2gufcojkg.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2ksdzymub.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewdkse.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2entsqell.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2cnnnfget.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2gzwhwhfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2gihsfajp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gt2pghyqjko.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2odxvausy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2lanvmahd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vpwqfmdd.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2pjgkrdzm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gucewawo.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2lsryducw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2lflndvug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mehtazul.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2xdfgadkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2ratedrpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gt2rvoooopi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2jshalsny.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2gfevpuwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gt2ijzvnlqy.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2miukxbsi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhzamcgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2jcnjcytm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2qedjzivo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyngxstn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2njshdtaa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2cusczmjw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgimmuvv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2wsmozrcu.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2wonnklft.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioqtjuco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2imqeklfq.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2qvgpatza.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmgytffc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ihdgvkev.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2hrcxvaur.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2symjylxt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2qauwpmae.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2zeqlkezz.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2seenqgvi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2pyvllwev.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2ftmhqwwr.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwtdwtuh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2qqfwujtj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2nowaconj.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2qwsvnisx.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2cguoczqx.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gt2dauvetxh.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2zdrmkcux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2ujfmsnni.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2ckigcfcg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zlhkmsqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rxpmpvas.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxobmqqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2zdyyuwbd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2ziqoornx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2oviwcxcf.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gt2stynblgl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2auzgyonb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhkbxblq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2fypvtjpa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2potzpncw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2qhhutgis.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2ngfnmtdq.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2gtheryco.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2aahqvotd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfdaensw.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2gfvbfbvy.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2cvtlvgic.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2czszrugd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gt2djdwwgwh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mersdvwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2hgwvgzrw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2rncarack.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2jkyqyjgk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2crrrzbuq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2awalogpw.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2rtimlvgi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gt2doillosm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2mwurxxpk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2upkhyazt.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2ijoruufn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gt2uezlfuxg.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2gzjcbwgi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2iewevkgw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2ftyijktd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2mpmimkua.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gt2izanvqmu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2bhutisrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2vtesmoxp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2cakilztt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2zhxjarhu.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoabuzfh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2ngohwhlg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2gxxcafhy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2gfugwhcu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2hjdiduhe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2zktdxvvo.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gt2dkcpyrha.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2epiucjua.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2hfkewlje.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jvqvlbcr.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2njroyplw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2amfxkjhz.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2dfnjypir.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2mgetrtlz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2xpcgqarj.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2xlbzsfhm.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2kkyprzna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gt2jizjeyjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2zqaoaror.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2hqlcpphm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfetqjkw.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2lvrpbyts.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zfcuxtfl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcnidfez.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gt2dwjjtmas.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2guynzcgz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2izqvlsut.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2flrxuvnw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2hsdmgxkj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2nwassmde.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2yszlmbqq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2jlnkdine.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ruccpdnd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebyzqnde.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2xcnrejpw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2argraawy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2tpyrhtyu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gt2ylvgnjvb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdmzahwi.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2nrhakgsc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2ndjfxttg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2fgygmuxf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rkvaxkil.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2hxhbmwsv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ebgcbjgt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2hglewfih.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2wjgtqrtk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2bnpchmeq.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmyyemwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gt2styokwcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2glocbrdt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ouvnmeei.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2atloqbwk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2ndrrxzuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2lpqtagma.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2ixbldyvv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2ihkycfwe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gt2prqvzbra.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2vcikpgny.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2vbrkjsxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2wxxtunmw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2wuxlsxfy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2blmzqiva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gt2zfskfugg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2mthuklhk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2cadaimcp.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2nbhrzpta.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2kwkdevyb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2qnxktraa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2mpyhbhtf.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2wsliwdid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gt2mhzpnodp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnlxpnub.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2wdbnpggd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isrvdgiu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2poqtfmfw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2mbxdahcx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bndqyedy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2kjoqgpsi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2opmfjpcc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2mqlweuse.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2kxtqmesd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2jplelqah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2ryhbipba.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2omysdcwq.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2tsbnatzv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kyoykkot.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2jctiknwb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksiytivi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2alejutek.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2qpztdfbg.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycekbxqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2rwkokirk.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2dgeaadfe.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2eopbvlwr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gt2wnowqqzl.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2qcewjwhz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2tczoplay.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2uvzjcdxu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2ftwfnqht.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gt2ecwvcebe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2cqxlmioi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2lupcrfrw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2hzwjrgnn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2wpyguqvr.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gt2kkhqnrck.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2vbhsctuw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2luqzvmja.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxrthemm.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2qnhqutzj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2wmrfhgqe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2dmouuhzb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddbmmjjk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2olxyxivx.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2royvhmql.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncchzjmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqdckbwi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2iujabwgo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2jpelrqsr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2oflwserz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2kkqtorhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2twfblqkd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2vjjkzovu.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gt2mpqoarkg.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2evyzhaqp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2akcqqhhp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2hzikmnwl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2mvrgovrb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gt2pbbvjahc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2avsisijv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmbhduq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2twylqgbg.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2rubydufq.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kytkykxx.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2umswxquz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2uakawanc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhlieood.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2jrsbqfxm.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2uaacyxkt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nraczdux.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpzsoaas.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2oeklwknx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2sivyysfm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gt2duwguhpg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dglckmji.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2zcnykwzd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2kdbpvhtj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gt2ugsgfguv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2loyypgrp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2hhgqjgma.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2lgjopsnu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2lrswzhgt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2mjvnzdgs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2dqzwpwtn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2xqrlqmzn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2hcclwczm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2hbuggrku.html


<!-- 参考信息 -->