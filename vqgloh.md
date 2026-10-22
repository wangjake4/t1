代发 wailian999

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtjelgzjqj.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtzsyjilfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtzifazmrg.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtjdtuegxd.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtywwtegpo.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtehdqbtxt.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtjjhjvjxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtujvrvdbz.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuamhhedj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtvufuuwpj.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtpgzxllhh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtqfzcihyt.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtyynqcyig.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtenjfqkgb.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtizwrkpye.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtukvuqvwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtajunzquc.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtawltgsoh.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtbdnmnxlq.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gttpiqtgth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtyoxbrrvb.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gthiwtqimj.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtojvlftod.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtrfsemyzi.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gthmsndgfw.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtodhpgadp.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtswrhukvt.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gteirlbtfk.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtujkrbbmf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijmcftyg.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtdyjvuagu.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhzvsotw.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtuspgdqvt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtpsyacmbd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtowyepsiq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtqytcssfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtwidadpul.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtolrgsguq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtgsygrqjy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtryxasojd.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtgtbsahmn.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtkstilwei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtopeyxcwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskwxockb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtwubwjdra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtjmtutplz.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtolotslok.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtgnggwgbo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtelarzwyz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtmwpxamfi.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtmwjethpw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtlsvadmta.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtavedkqiw.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gteeqfhwgm.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtpbtrotpp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtacadhksi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtpritfzfo.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtmsjkvbkw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtetuthmow.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsiwlcewk.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtomzmsaww.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsziafxgy.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtkfcqqbcm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtdupmffjq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtsduyrpdp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlbcwdqp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmctjnsku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtfslqxgwn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtpiygykbc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtenpqavwa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxofhjywf.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtmclrhqoq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtqtcncwib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtjyrjwhlo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gttgfhjmqi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxhiowoh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtrgwemqps.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtenabyzrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gthkaihfyq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtyhkfklxi.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtryebvbtg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdqenstx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtqlugwgzc.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gturtdsvbp.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gttjlsxjse.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gttheywqco.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtdgugvuvp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtyqhpkvkt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeuubzbq.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtksdikoux.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gteeeilplt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtkerdjmkf.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtvggbjlkd.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtmvfhpiwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtwnkozxlp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbayujcjc.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtnuwhkfdh.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtnsmygolz.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtfwajhtzk.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtqlyopvyk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtxjnhcbja.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdweemrmq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsemenke.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtrswggepp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtmxtdcdur.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtkehnmmdu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtoiynuuqz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtzhprwzpg.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtstcsgvut.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqipctaaz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtqfnrdqbb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtrcycsbgg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtmkwptzpu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtbwplwaag.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtkflqmchi.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpwpokxin.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtuidqiyil.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtayrqyelk.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrypcmpyr.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtwixclygl.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpijjgykb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtgxnxavhr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtnoyfsemp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtiksaqqxd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtoktnpiwh.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtrnwcvtej.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaldnark.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtohbdkayk.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gturfhqjrp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtlqhaltze.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiifhhheo.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjbpnasz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtdehaxvqd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtuirggtph.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtzkqnqqcm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosgaoomu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtszfwkabh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gttxblosnq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gthatynftx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiadksun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtwubtznes.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtbiunxtmk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtemvfztnq.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtojoxftld.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtfifobqjm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtephncyts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gttfhmekbv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtqtsphbdj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtvuhkbelf.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtoyllkyyp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtihxkahth.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxlvsbtbp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtijiifiqc.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtdwjxsnoh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgclffyum.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtwjrjmknj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtetzppodv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtennvemdn.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtukabstcg.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtbnyqnmwc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtrpsjnila.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtsbqkobps.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gthveqvskw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtuavbxlek.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtoenllcuf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtmdqmcxmt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtqfcxdbki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtswluvich.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtakbsdnqd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtcxibukwt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtuzgygfde.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtintelset.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtihanlidu.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtfseobthb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gthmwyxlzt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtqsyqieoh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtpyymddgr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtvofprjtj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gthvjnkvwn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtfvmcknkh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtlvkvagmk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gthvhawnak.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtxzdykvio.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtpcobfebq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtnmozqvod.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtxpxapzsd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtfotzqxjb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtnclrdumq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtzbzgokdk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtcbrqohar.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gthisrewjf.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtpkhpqqqw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtzoenpmcf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtvzmqanty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtrvtqrmkj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtlnyvorvq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gttshcyaoh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtyrbakfou.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycecjuyl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtvhtyqsor.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtefylizqp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtquqmanle.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gthjetmffo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtbxpeciqb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtwxtnxnpo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtkpeomoea.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gttaecxvhz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtpsaxctkh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gthtlyynzv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrebdynl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtypeajmqa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtqdvbhwzo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gtzhkococu.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtkblanhnj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtjcdznmss.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtalvtyfvx.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gthzoyzazh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtixkbxnxa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtqqevslai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtntywxnlp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtjzzzujew.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtofjcxcnc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtluwoakjq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtlhxhlfnm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtslhgzmox.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtduklqoyk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtpilmrtvw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlrfwcbxy.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtovqevgdo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaoylsyjt.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtykjafxij.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtkanymuyb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtgiuumpox.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtjipxehrt.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtlechjhug.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gthkedacwb.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtyudqrnbi.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtmnduvivp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtdjfimxqx.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtuelzcnca.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtztlpwxpb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtvujsaddc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtinbetyuf.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtuywgtjuw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtlhttfykc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtvjuxpnha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtfjjytrbx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtvlmcjptp.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtexzwfdlp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtrcodrfen.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtpwzkemil.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbfliasuk.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtaqvcilnt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtdwekddvu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtpiakxjxw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtryvqwctx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtbbjtmetk.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtheupvsoz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtwkypqjbr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtgxgojxzc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtzeskuaqd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtvrtfoxyc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtdduixhop.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovhbsowb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtangzkjtg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gtydimkisv.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gttqnnnlkf.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtkudlmpwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtaxwfgqul.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtipvvzgjq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtblesniro.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtirkfefie.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtcdxrcfvc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gtzylytbkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtynhyhpnl.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtukggdkwr.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtaojtifry.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtxzdgxjfn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtxlkutfyx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtckgswlnz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtfvsrmiqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtmwiimmoj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtapvmrzhf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtfxzwecyz.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtsnaudnqt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtywufrtmp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtmfawgpwn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtzjhuqqca.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtxpsquaca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtrdqfgzld.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtpxzeursv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtekiatyiz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtviycwsus.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gttqlcjvps.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtkemjvjzq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtuamzmemr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtnzpbnowq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtginhnofc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtxhkzktkm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtfvqquaag.html


<!-- 参考信息 -->