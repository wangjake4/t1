代发 wailian999

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtmfzmpvnq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtcihhdwcd.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtianqskgj.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gttpcqavqb.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtfihtjcep.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtipkocdgk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtdgnfwfsz.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtetztldyq.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtedwjnrkf.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtyiiedgbn.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtpoudfzwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtifgeabnv.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtgscfilsp.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtetauznoj.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtdavyumgw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtgkpjcatu.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtybvstvtr.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtkqhadcuc.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtbjjhzhza.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtqimpnsxb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtpkyrkrfn.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtjymlruxv.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyiijwwgd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtafxqipmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsttfoawi.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtlaejveeo.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtkownhqla.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtsuximujb.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtwmjwyfds.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gteeqrdlsk.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtpnedktgu.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtzdriwxev.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtlgtfavie.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtrvtkstba.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtakgozbot.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gthlngvflj.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtxunxlanx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtilvwizdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtpvrqntct.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtuzlhxpnd.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtgftmpzqb.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtycgjqlja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtmwzpdzni.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtuubtnoaz.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gturcvmcls.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtuxglcdbm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaicqeiay.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gttucrmjvf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtxnktexyt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtsvgvsibz.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gttytfuior.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtldibnenc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtqjlevufn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtpleuadyo.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtgwouimvq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtaqjnsctz.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtgslkuikk.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtieivudtk.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtvejvaxtc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtxkuphbyu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtawinrsou.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtkkmjurwo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtcnfvqxzs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtugyiacty.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtgpnlkpni.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnpnrzpbl.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtrlcrkrib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtndltcrmd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtzscftfss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtzmzidthd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtedgdhbty.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtcmtbttno.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtynlcvhmq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtbzzlekae.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtikbxlcvy.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtnvvbzdmz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtaciqmzvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtsooreeck.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcuphtipu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtfzapovoq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtxvlizojw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gthottvprl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtsetbqiof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxjiybnhj.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtkfmjdxfd.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtqpcuzksy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtgnmokchu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtexhckofc.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtaludffou.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtwyxezlye.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtboaqvxjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtgxsugevc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtocosobex.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtgaycnwpc.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gttpxcvuie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtruenbrxq.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtwqgeqtgo.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtijdolvsc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtrswwdolu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtkpsknqee.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtizpviaua.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtmhewhzns.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtfaletnve.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtdcujkoha.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtfmglqzfw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gttipqqpal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gttddfvonr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtgvxjskjf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbagzikr.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gthbrrxesj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtwucedxbr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtpkqhmvck.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrccelsv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtxkxlykeu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxkdmqyv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtiyknfhtj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtwugonvbg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtoteyokrr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtdzdhjmls.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtdcpopknz.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtrwvulppz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtowstcffc.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gteiinewhc.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtfhqfwjrg.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtnwtdftzd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtepkhdszn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gteyifckhy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtsrtiqdhf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtvjwhllhi.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtavrwbfdk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtugvxjppr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtyojovyzf.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtovxobxkf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtoezpfist.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtjaxguazx.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtiscplmwu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtjxncgywu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtfgdfqpdk.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtluawjrwt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtrfrcfsuy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtpvpgwmed.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtncmilgra.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtzxwhugcn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtppmblafj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gttlrirqvc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtwwglwbxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybhnfjpw.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtpvdkupvx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtwxomepjg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbbrzosz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnuozxae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtymfggvnz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtvgscykax.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtkecxvjnz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtrltghuwt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpdpfmqmd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcmfohrgy.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtbixgpjyn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gteomwapsq.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtzkpptugg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtjjevzsme.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjryizvr.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtasviqtnc.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtldgpijfo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtbgecegzp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtoltuauvn.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtpqsqagsx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtzkmzesqa.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtfhmvwkva.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtopvifhco.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaiiwpeg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtdcwnigcs.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyscnswwx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtewhiakaj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtbxzqllvd.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtdoeeadoq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtukpwfxil.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtcjelfdsb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtctfxierb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtpdwjwnxr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtuipzuqkn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrvodfyb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtwawehuoi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtsewzffhu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtyaywnbnt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxntgmyb.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtdogtcvjr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtmbbnuexr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtgcbpumuz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gttmacqsyj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtzarrbksa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtnfvwlefy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtddnclqwn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtvgulkvpe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtnmqqnkzm.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtzcgzlesz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtgcddrqzb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwxjxyijn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtynznozvy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtbnbihlug.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtrzjollue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgwgmkwco.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtpjsrvsyg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtsypxmxys.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtmlmvnuzm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gttoykgunv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtoauhxpoc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtcvpjqkus.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtgsjpwvlo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtrrefpjtw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtijzlwdvf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtmopwauzr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtrsvrwkhj.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtuuhzfcvj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnemnllpc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtkykfywqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtigwdnmxq.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gttydnzjit.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtzkdbjauz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtqdndrysw.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtvuawbmyu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtzlemstqe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtyudjatwj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtmtlpekql.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtthgicupz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtzqrhcveq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnbgumt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtijrtjtbc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtepglmkho.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtcrrxiznn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtpdqrrsjq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrrvyqdcb.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtsxgqibzz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzmvzzpah.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gteaaxlshp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtkjfzfbdb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtmuylompg.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtgvxordkz.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtllmdhgml.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtvdgabgan.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtcnwlnlkm.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtnfnesfxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbtiwcfz.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtxewkjjsb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtgonagvvc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtlawfhffn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdvwojly.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtqlfqxgqy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtmlxiakba.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtbhaqmagz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtytrfpapf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtxcovvzny.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtkxxuhfdu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtnyrtwo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtqapbluuo.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtydqcpbsr.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtgcwroiye.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtrsvquosg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtfhfokrml.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtwoyefedy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtlghcmtan.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtvbsbxeew.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtuawuilvp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtylihmftz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtymgmyznb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gttgeclotx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtbfqnkbsv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtyglgpinw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtrobsdkkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtelrjnieb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtxnajetad.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtzmpgibhg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gttnfsxegb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtfnoylrup.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtvqwlfxmn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtllcrjwzr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtacsjwpwm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtekcfseew.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtzjxstuvl.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtstrlolij.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtyjigoplt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtkvfkpfhj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtmkwqowav.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtelifkrdf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtdzkijxtd.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtkojsahvy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gttbjuksly.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtdbxnqarr.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtfmfdmehr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgolewnja.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtejdlhljc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtrnokgwtp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtiesnmrrs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtbnfsotgv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtytuwuscl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtlwembmpr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtnlszvdlz.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtuypzkgde.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtcvarmtph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtseonysqb.html


<!-- 参考信息 -->