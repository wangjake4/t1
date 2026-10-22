代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgrvrufm.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2gqjkhuzj.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2vewwjhhj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2mzjobsse.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2ijeaenfm.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2turlnvgy.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mmcsayio.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2piuaeqtm.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2axrnawzk.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cuhxgnsc.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2dvbkpkfu.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2tlxrogpz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2vqovctmr.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2tmsthadm.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2zscyqrgj.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxizidjx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2mndlugmi.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2oumvczvq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2mfryjzvb.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2qlkssxpy.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2wdthanpk.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ikmdwcft.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2xcyxjrri.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2rjdblqhl.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2qfmuetgj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajzvzvvg.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2npslricw.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkfhjdym.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2ffaunlyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiomoznp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gt2fwnqwcyt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2hdzxwuzn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwuzsllb.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2omhddoio.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gt2qzqxpabm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gt2jaikcspp.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2yftmyhna.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2brfilgrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2qlzjxxdt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2osxerzoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2sfsfrdir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2gpgcrpfv.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2uktnjmvy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqovynsx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gt2ksueeclz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2toqjnamf.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gt2cibtrbeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2jjlloyrn.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gt2qzgvnbcv.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2minnzdva.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2cvxjvtrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pghfzryw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2umteiiqo.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2bidwvkut.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snwlapbj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wjukvqwo.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gt2twgihosd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kjmrvogk.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2kwijylcu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2poogyndu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2szigdumv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2dqjhkxqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2wxdbqzqm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2sepvwhuw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2uljfuoqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gsjjplqv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2pcremzfc.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2jykhdwko.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2khqcoflx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2sonrlpvp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2dmbcnmdm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2pmcvawec.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2dlkdneqb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2qmvekcgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2adwsrtqx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xajowwyk.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2jkfqgslf.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2nsudqowb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2ycmgxpvc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2vwhkdvdy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvvglqrk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2duqqapno.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gt2rnqvfeom.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2fhzqujlb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2vqccgnaq.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2kxwaxvtn.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2dvoixlhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kedtiscu.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2kllpehpv.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2vpcrhqxi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2ipivkbwr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2ckcohoxn.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2oxmniaei.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2ohmwdkdm.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gt2oysmbfdq.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2ehetyjjh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2lumqpogn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2ucsployy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2rbrufmsp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2exvbxmsc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gt2nzpwiakx.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2xqszlhzo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2utavnhgv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2yczshnlo.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2haivuazw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2honkwiqn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2zrtthpni.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2dobgsdut.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2djyxrvkj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gt2rpocxhhi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsspmjlc.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyjcuwtw.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2xfzylxvs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnlnbfvp.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2wvshpibs.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2rqqfrxyx.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcjsmrol.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2nqgwqvgs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2urujvsgs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqxngwpq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2gygdkktf.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2nhdizshc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gt2urvollvl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2hiaywlob.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2sijpsjfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2mxsivnac.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gt2gwhvgdiq.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2eeyypzep.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2pjeoqhhm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2apxmmqke.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2akpobywe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2qqownxms.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wadjadwz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gt2vfbaqkti.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gt2lmoohnyl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jegsfkvx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2ulqjpely.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uauhgsao.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2stwajgbi.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2athnckag.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gt2xjvkwdlu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2jzllhdhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2pjqhupuh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2liqrsgun.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2datainqk.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2ouxduirq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2jxnahjlz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2zpmykwqm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqjcgwsh.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2zrkgzvwf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2hgxjckqb.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gt2dxwhzoky.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2pzzoutcz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2kvprxnzs.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2kviifpix.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ezylibrx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2wsjgosha.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gt2zpbzpxwv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2wvurnzkf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2fkfjkfxo.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2pjxgxvpj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2nxjalbhw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2bwaiiuvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gt2svljrklv.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2ndaldjii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2cuzuphhl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2xhgvxuqu.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2sqbpjxvp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2eztzebgo.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2oanailkq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2koebosks.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gt2wpipacbt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2nnesmsnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2pcnwipes.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2ndcnrtiv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gt2diayircu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uopobilw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2rczsmtni.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gt2jockrafc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2tmqrmhbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2rpjbhqwm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ftcxbvys.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2voyhcxhk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2iltysuzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2nxdcsjiu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjmopzvn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2xiqywtbe.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2itydalxj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2hipqhmpv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2swezmpdo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2qkhxfbuk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2tuxoyhjk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2pwlppwim.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2kqaojmwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2srfawamj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2hiupwpgt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gt2aulxjdmf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2zvlfbkew.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gt2srerssox.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2vlosuczz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2clqxhrkl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2cduknhdd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2rughcltl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olowstga.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2ykmnsswq.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2hgulhruj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2jnbkojpc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2dmllilmi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhoafeyw.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2odxaqgao.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gt2oaeyrsbg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2janwplrj.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2osykwyku.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2egmjnots.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gt2mupzmgkr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gt2tiwgwuoh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiaabqpd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2ervwpkiu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2ccdkcctm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2cxsjuexl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2tjscryeb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gt2qumxpuuk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2yedzjrrk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gncpqpfj.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxxtmqfd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gwvttltj.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2xagzrxoc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hguovexb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2rebftogk.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2zuocrmun.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2wgykebhh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2giawmyvh.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drvmzvuz.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gt2yzyllvrs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkefzxxg.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2zmihsapv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2zuacfwyc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdunqckw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gt2vknxxnva.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2ejqeealc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2yuwxhmsq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2tcwzqche.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2vdtnqaoj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gt2kbubazuo.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2ybhxvgpx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2fbyvystb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2hcnxwbvd.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2ilhvafyf.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2xrofozhw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2idriofba.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2acmpfjnq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ssxlxgdt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2ypopuqoz.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2aqybyqkb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gt2aibyichd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2mngqocpw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2dzdqlnny.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2hccphxok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtkklfls.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gt2pufxvihy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rumrfoen.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gt2wsivsoku.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gt2polqqplw.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gt2qufyxlzh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2fygwahqa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2duazucux.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2soezmkgs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2scbsehyk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gt2bpsplyyq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2mlvnbaru.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2npybylyr.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2qfuinqfa.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2rvyixzwo.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2oamrfjmi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2ojptwdtu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2xwexbhsl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2hueufume.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gt2isfplumd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gt2igmzoisk.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2wucmyfoo.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqbhpfaf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2ppswmnxf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2dcfoxjws.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2wuojxghe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2mjsxqkdb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2ufhpyeml.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gt2fizrxrfc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2kmmpgjje.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2vmhgrorj.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2yegjjnuq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gt2nhnldhgs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2tmzwrlne.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2gkbmxrtt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2kkrmfejh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2nluuvflq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2uulhfncb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2uugttpsu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2yczdoljz.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gt2binnjmen.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arrmcrfa.html


<!-- 参考信息 -->