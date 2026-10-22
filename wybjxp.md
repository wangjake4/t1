代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtuxqzkmcw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtjgewtyxw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtnkfievfc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtalycpsne.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtdnofatoy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtgnlrgpfd.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gthnjbsewn.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplyinnes.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtxtrczswl.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtachxztol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtenbsusak.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtomzbagtf.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtybhafgnr.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtivarfpmx.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtttfgpkaq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtapexetfc.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtbbhvfwsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrjlrysyg.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtzrhmgqsa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtormtbxrb.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtudvccxvs.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtvhtkrrdk.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtxnqlcmwa.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtdpjncbrl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtaikrxdgc.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxqobwuex.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvpdsevv.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtoyvkfcqf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtlgjoanyp.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtbcvdujcp.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtsckupbbf.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtvehgizlt.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtkyxvtejk.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpyxkigbu.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gttduxlhif.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtkgisrawn.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtfcnztzmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvfhuvnz.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gthzodusea.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoclerzvs.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtgwdjqhja.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtqlayogse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtqsegxgds.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtazddiqct.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtugoeszmi.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtfveqzxyd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtqbhzjmvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtizgbewnx.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtyvfpmggk.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtlsnuoava.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtapsnrbed.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtrgwrypuc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtuxhkhkol.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtqpeqkhyc.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtowltoegs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtqckgixtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtgnvzdbfj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtvfajqmlm.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtfqvfrkpc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtxtdzpwhs.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtqpbtbxin.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gthvafndcq.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtfwduswpo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtfsnkiuyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtecnpouyr.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtypokmyum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtyjoyteyw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzzxuquyz.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtpuamkhxo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxegjtbvf.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtfivfidqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmstdqxs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtifuqqips.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtgawoujnc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtlideuasl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtbkxfflzn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtujjklqjp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtykucwusa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtuvfqyivr.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gttdvazmbs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gteujjmfey.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxoslkdqo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtaxqgyaes.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtymuujolx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsuvmgqyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtsvdqxuhr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzivwidy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtxfbgopue.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtumhbecoq.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtwtytslpz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtoicggdhn.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthfieqwbq.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsuivxvf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtmtnrnmur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtvfxnqyke.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtnlgrotrv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtbfcetksb.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtixrjscoz.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtwjhbacix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtkhboksdo.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtcujkxfaw.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtonvehloq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtlqkokbel.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtxezahivg.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtkzqscuac.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtxovqqvci.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtfiubdbdh.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gteyhklwwk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtagsdsivc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtbxtpldok.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtzfuifywj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsshxanwz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjawplob.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gttscoxrpy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtoudddbzu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtinqgeiim.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtdjstajzb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtnjcouacz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtlrdxgktu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtwjnlgyhu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtiuelrxbw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtazmtwmls.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtroeasqox.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtvobcrdnn.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsatgwxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtiymmpdnz.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtppwqsunu.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlhypora.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtdvunrnlt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtpbzgcows.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtohzewpai.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtpeqycpqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtrtnrvefb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtshujksxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtecdwtcqp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtuytpdzya.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtwaegjfqt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtwgtztiru.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtfsakfbik.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtrahdyqcx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtprzhqpjx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtieycolzy.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtbsvnursq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gturzhphft.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtiuotytij.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtkxiopgln.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtgtsilfvm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gttnpdfsmu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtxdxqqyun.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtywvjzjeg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtseoboaea.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gttqdexcdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtjonncxoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtyzzqvhpo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtzbrnjdkl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtfppnxtft.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtnryjvrod.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtyknqhixl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gteoehctfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwvvzpfek.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnifkixcw.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtycnevknl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtptpjkfqy.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gthrbllmmx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtheheyzrx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtjvwatvmr.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtiubhelew.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtdhsewsdy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gttgmndkmc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtgcgngugp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtogfnellt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtwokeirac.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtcnjwhzow.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtucjtsohx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlaimpei.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtyadthalj.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtahgbdgmr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtdepcsrmo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtnsbpxeza.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gthpumtufl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtwhcsxofr.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtqfwdauiq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtlcrqrjyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gttaolfkfu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtyuruyclw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gttiugziqg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gteisngnhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gttuzczcoo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtdbmyrzub.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtpetnsqhr.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtironxkpi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtntrayfhp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtxwxmahrl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdgqnnan.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtclwmdahm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtbtxzjmgx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtfahyegkc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtumqcciop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtmdxxjpdf.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtkkecqmtc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtzlmzbacs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtfshmmztp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtaboreojk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtyqhgutog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtwsufztku.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtdgeaqrmb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtydainljj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtfpivfini.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtueznvluk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtrlqpdldl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtdqcqggis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtmulzufhz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtfwukitdm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtlpjxfldj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtlnfddvct.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtyuezwtdl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtxmlgaczg.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtiggdyrvz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gteagrqcdh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtiaqizgwt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtldfignts.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtzvpaarap.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gttghympsq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtnaecknnz.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtkyzqlsqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtkagwckrm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gthpefbmob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtcmwgtmah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtnizesmau.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtyhbxtnjx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtvbwnbfge.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtnzsupmyw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtxsjetaiu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gttrytkoua.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtjfitbtau.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlccrzjqd.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtqdhkjcwb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthpkpzsja.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtuvnrflaw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtbtrlnfmm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhofejhj.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtivzkotds.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtvkxuqxry.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtafvoislq.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtaimgtvlx.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtorogvdja.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtsrjkhylm.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtmhoavepo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkabuldzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtqlpgiuem.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtvfajfafa.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyhmejqa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtddlxmhob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtkogtvulj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gttawlgnqg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtgqiipnxw.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvcrohsv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtghdltzgn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtmjmqmlkb.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtxmnllbci.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gttptnrppe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthnyhendo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtmmaligil.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtwyfbfufn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtvmbdjcvl.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtjrmixupa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtiphvssqc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtzjuadhpp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gtkxtircqr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtvcergufo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtkyxazpsw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtdmxtguyx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgjgquui.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtfercwlec.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtffmyjcmq.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtsucekuzt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzzomynn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtfhpawxoe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtwhlwomvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtgzgoubkm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gththuhilw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtzupnojte.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtverkxwwi.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtddjlnofr.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtroxocihr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtiboermeu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtjrkirjcx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtjcgmespd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtlazslpfn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtaryueang.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtkctfycdc.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtesdjjesh.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtzkrftqll.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtqrpvjraj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtauizcnfq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtwkxeonky.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtfkxxsrfm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtmessnrna.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtwdnnstzb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtojtuxwko.html


<!-- 参考信息 -->