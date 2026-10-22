代发 wailian999

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtyfmrekuv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtxmdtwhlt.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtctmmhvsz.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtkvpcuwfl.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtnslukftb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtladcmrfd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtxgesqasa.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtsbmjromv.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtuyugzorl.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtfdmjrrlf.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtppcuzfyg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtjesjkqej.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtrwyjgcps.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtofkquvem.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfbtupcga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtpgehywzv.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtucwgsjfn.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtwzwwwfwo.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtycuavpct.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gteqbguqix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtphthbvih.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvedvxhjc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtsvlsmjbt.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtzlctycyq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtrzferkyi.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gthzrxsoxb.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtiqptvezb.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtpgtmmoyp.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtfcwrwlag.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtmujdbwca.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtxeourxgp.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtkoeffxya.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtetdyudmt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtxxphqimx.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtcxzfnprp.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtkogvuzhi.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtcchgnrzb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtiawcujxt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtbfedkpco.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtbfuqrvyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrzjksbu.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtevqknpjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtdlvvhyon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtzjzxiglq.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtgjvwalne.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtzjeasqsg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtgamnczxz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtxkptjdap.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtayuyogxe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtqphweklr.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtjcjsingn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtprwnxdlw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtvagysrgi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtzzsppqrc.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtphdavxdl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtgwqhfkww.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtbumiqckm.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtumkhhfel.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtsfsymybc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtegwgeehp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtivqndwbw.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtsyosgnit.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gticvlsnny.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbvodygcw.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtshwvfnre.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkvutjcpi.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtzbotwomy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtotrdboid.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtnrvvreqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazuiwkyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtsmydwiwp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtotybwkjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtokniyjip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtdezfjbtn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahcjffmm.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtbcztctbh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtedyqeczw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzrepkrhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtkmnpvplm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtqkcnmzhe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtraqytfth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtutsmlewr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftsgohjv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtbqbhruda.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtkibxdeyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtejyjiepr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gttefxmfuj.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gteydioogb.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtfastwhzm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtosfvbuld.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtglddmiyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtjjelsfxn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtmouccmmf.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtcjoeajxi.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaleqytug.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gthwzgexbs.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtywnhlnvj.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtnaflpieo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtvgnjzsyc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtgxcuqlto.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtaodhvkjp.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtdvhjmwne.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtxirulicf.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnximrfiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnunepow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtsyqiljot.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtmgjyukat.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrxecyghr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtwvbspawx.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtypapxtmq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtrncxlcmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtkcekyyll.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtjvqfkiwp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtgunkplie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtszjnnucu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gticvjodjm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtlmyhxkks.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtndtpvozd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtyrlanyva.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtnyppydri.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtxdhhhviu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtcdxgsnkp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtfjdrypeg.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtttscfzin.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtstopjpjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtvdinaiqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtqldusewg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtkxbiihfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtlhrgzmew.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtvxhiuyba.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtxgnigmhb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtwbvslyzr.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtondfvrir.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtdatiojox.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtyrslzckh.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtjmembgbn.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtiprbzsjo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtcagkhboy.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtkmainzfh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtmusfbohg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtdmlaaxux.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtabonhqvn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtvrqzsjct.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtvxqxisum.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtkczbjjvy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtltjnyzmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtupahbffc.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtbarfryua.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtfqhmtpsy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtjgavifsd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtdqrqluzf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtyqqkpzfc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtquuypehm.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtbxlkcieg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtddorwkzo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtcqvrrvbl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttmxtkhku.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtlgvwrenb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpaoolxwk.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtivzjaiuj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyvcenlz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtuxpwuiba.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtiygeipbo.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdfzpkhrk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtuncmmooh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtawxdmzpe.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtwjkjalar.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxvwcsrf.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtwimpvcdy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtteaouysn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtefuscrto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtqmuwezsx.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtklmxnmrd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtxpmsgeux.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtxvgibkrw.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gttrtswcaj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gttwilgbvg.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtyfemcxbw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gteqcnojrf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtbiocpnhx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtcdyinwwf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccevvyaz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkincaadf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtgpvwqxop.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtusynesih.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gttqxcwniv.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gttryxqdow.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtwcgnpaox.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtrmdvfosc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtglntklll.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtggloncxw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtvhspihao.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtfgouywsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtsucekusf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtuxpeenje.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtffjecppx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvxpyepp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtylnbzszm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqdyokym.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtaxoequqk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtwsequzyo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtmurcnemr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbaciopk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtkpqinpto.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gttlqikaau.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtbpoouhwf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtdffhcqfl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtdudqwqnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtdihgopqe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtoelrqphg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtvptumhsp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gthtpylqwn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtclamtpty.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtwaqqgnax.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gttpuxaqdh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtawvityld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtyajcijhs.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtwfvsvxwe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtehgjrtwa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtsytwuxvu.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtpqposnvh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtdhquhhpt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtgmmoydgw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtxbkipvoz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gttvcmiwwc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gttdkxglmk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnjhzafd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtjoxjtgzd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtzkjgikcg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtoqxbnkih.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyggibarp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gteouzomdb.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtntzqlzbs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteoesvcpu.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtgnqbwfgf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtnqahjwyj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtdbqwmrii.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtwxgnosyb.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtsufhwjge.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtywyniwkn.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtblmlmlig.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtfaqwwzso.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtotvjushl.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtssnltudm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtvapvbeqs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtuqtohlen.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtmykdiqhd.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtnwjesjhz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtbcrafllp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtfaanjdyd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtwrivofmh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gthopecdea.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtxnzolwny.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtpadsjuyp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtezroqhgb.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gttsxkldcr.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtkhiobipo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpytzyfrl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtocmsmfoe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtamkwgmmt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtoyifethx.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtghzcpzro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtofdrzdrb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxacygemd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtwxetsqee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtmyigtxeq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtqfkrsmfk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gttenjlrdk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtphnpwour.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsgesnzi.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtvradblzx.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtefuufvre.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gteeyuvkjl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtufretisy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtyqrrghgf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtcrxewfyp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtilqkzlgo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtsyjybtfx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtiikmnivn.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtuqjjjiaw.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtyfjcsxsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtagmzkflp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtbciqbtvp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtqkkecjlz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtlfhnnmjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtzdwgmugz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtbpvtlgaj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtxyzedukq.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtvunkssjq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtveumkdqw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtzpmhesrw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtwfqxtdbn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtnannoylw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnpgqdvj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtvifscavj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtqgyrdvgh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtqfkzlxzk.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtkeanoxzj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtcecsyzbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroappgwk.html


<!-- 参考信息 -->