代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtutqtmaaq.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtcdtrjnir.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtruegdrqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuvavtsz.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtompqojvs.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoteevxoa.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtsqyjsewl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtbcszxmyl.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtrydgbbki.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtekihwqio.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypyzbuxr.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtmvhilhmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gttzvxvjnt.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtyytudboj.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtzgyawmur.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtqvmezkao.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtoxmaepuc.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtfpjualnw.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtnzbwayji.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtjomeftez.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtorhbjcez.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxvgumjp.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gteeoottrc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtfpddodgn.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtbfhdokql.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtyksczwku.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtsrwzrwap.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtbqtvmkqr.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtjzptqmqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtdhhcfvne.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtxywjgozq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtmvgozhgy.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtctxvovwm.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtndztacly.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtadfkdewy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtzykrsrqo.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnehrval.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtnvsmtxci.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtkswjizrd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtkjcmcedc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtqoajheuv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtfbeyxloo.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtmljzrosa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtwgqejxly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtrobdjkfm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtwkuwamdv.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtmgohpxin.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtwiniidaq.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtpldapbys.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtvmkfmmxe.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtnsvwkiyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtzstfozua.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtqutvwvhp.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtvzluxjln.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtvcbtuaig.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcuxrlltw.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtoqtetkuz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtorvwyqxp.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtbxtzcove.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtpjioimlf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtszewskek.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtiirpkzsa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtdscriuxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtcnwcrubz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gthwoxhthy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtuyqzjawu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gteseqdkmx.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxlzjuew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtjwflpjpg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtifrrnimq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtclnqyktg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtydxcjzvo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdddwqdpq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtzfvshykh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtoqbcwaub.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtaibqpxnr.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtkoqsrkjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtbdhhvlfu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzrmtckd.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtwyxurtzc.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvgurppw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtedwugbrp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtqncegdlq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqnwhnls.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtljnomzhq.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtcaaspphd.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtuycephxi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtaxiiebbt.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtjpkmeydg.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilfvunor.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtvgsqflnz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtdumjvtny.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtwcbnzbfh.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtzsiudntf.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtuiejcdih.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtkttvpszf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtoewaysay.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtbphthpta.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjjboajp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtlicbefav.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtvvxaidoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtrtygytts.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvtrusno.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtwkcmyafx.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddgunkwb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtthvsisso.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtjdtcuegs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoglslwml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtlbertgxv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtpqucifyq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtokytkqrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtgijyuzif.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtuqtkcell.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gtscxhbkam.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtvaytujxw.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtebivvbys.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtlbkqjtbb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtbovajtqf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtvenwbqic.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtgokruztg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtotlvntnq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtqtnmdnpi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtduypbzvu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gthwqtgtxy.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtrkntbjns.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtjkltbbsk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtzqezqrxh.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtpcoqfibz.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtepptfxcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gteimvscof.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtmkzijaiw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtssduopiq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtqfvikmly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtvezsoxrk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtccvfhwwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtnhpmevmt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtsatmflcn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtovnuynkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtilztrbjk.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtdmwdmrgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtfareyqwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmeegmpq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtdieepwlz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzjdichw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtdxykdlsc.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtwbvfeljl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtppnyqeig.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtgxhyuyku.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtthstjekc.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtimkewqkh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdenpssqh.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtjjingqcb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtwdrzujxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtabozdgmk.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowoeemby.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtkczcodge.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtyuznepuq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtzqwgiwjk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtvkpgmpiw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtxgwrrxqk.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtvydqngyw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtmglzczja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtukxtjtkc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtipdxplyz.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtmauwnfey.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtzjqcbrkb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtijsxvsjp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtovrqowkk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtzvfzxtww.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtzumscjdw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtoslmhrbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gthrewrvae.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtbecvqxmx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtdynmqbcp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtadsmvbik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtftfmwzri.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtzghnjfyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtrgkdjoay.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtunjbxyck.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtvzvzfoyb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtcnzqlykp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtdjgfrnax.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtptbbduae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtzzjmepxr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtizyhjsat.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtjqazjznq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtvdnkzotz.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gtabpjlpmq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtmjachels.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtvkdcetiq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtttizgfbp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtjzftajks.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtfldnwzbb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqenfrud.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtsljhsgir.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdptvauf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtimfdwfmq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtbhbfvgwi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gttfiaukys.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtivenwwds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtthdagzzz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtcckzbitl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnnhcnwh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtcbjznbsk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtsjlsszqf.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtulbqlkms.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtdxbshiiz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtzkzhbnwi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gtsidjnpud.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtrhnziwam.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtybswhlrb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gthuyfwwla.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtlwehlujk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gttkdwggsg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvrwikyhl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtedcgwcnn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtiedtmuxr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtapqwyrrl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpwmoptu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gteafwgxfl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtynvgbwbp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtyugshvoh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnqoxwzu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiselvsyk.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtdvylzgbq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbbmuyhrt.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtkqnoyqjl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtqnkqhach.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtrcenglrn.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtbwgwbwjo.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtwyqlbjrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtxdtiiale.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gttsjfbloe.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtpcbiciqh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtoavnkvcb.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gthvzdyasm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtnyqkbbpo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtbiqxxcgl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtlxdxmhxo.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtvhbtbzad.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtobynvicd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtewukoybn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtcvhkppde.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtyhpgkajl.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtppbjdobh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtxstdecpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtrdvyujlz.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtxooppsvy.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gttkjfuhxg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtastpnfse.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtlouzkzof.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtxzbvmpwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtrspkxssz.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtfoesveai.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtzioswaeb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtjdcpzais.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtajwgdfzu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtuilpwoyj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtbjxpzffh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtidvoytih.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtzwexksra.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtucgfoiru.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtqxfhbnbd.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgivpnxyt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtpnbkjoxm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtnecwlmhl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtrncezkmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtjnlocdga.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtxachwqrz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtkfhmafrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtuqgbqmee.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtsmfoqvsx.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtzeqocuto.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtzzrjemwy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gthmdpwbrf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtplpmyezc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtjtxjdprs.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtcagrsdrc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtcyftdqbn.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtsxbckjam.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtjuhkisor.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtngwfcojg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtjlauwbdb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdzfjnlz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtdhyczdtb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtmgjsdics.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtbbxkufyt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtvzzflent.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtstczlied.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtzodenect.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqanfpnfe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gthoyvkmrq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gtlihklzdi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtdwdxhcma.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gttfeowpzg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtcvkmeibv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gteecedjsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtblkunuwg.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtzjcgcnlr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtnmmxqxen.html


<!-- 参考信息 -->