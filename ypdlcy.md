代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2njzcaffo.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2tmrpzpaq.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gt2zexumrtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2wwfyyrel.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2jhaowjsk.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2yzumoftz.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2kwewonmw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcucvuya.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2jgwjilas.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2womgaedf.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ygfrvqyf.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2mvgemqaj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2bluwikdv.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2doasxgek.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2ceaxzwfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2mhxiebmn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2yjxlerhd.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2frpxmugv.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2bxzhsrmw.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2jtniqdox.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2lpapmfue.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2nckxpowj.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2dvwblptl.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2wgotzofj.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2gebsutdt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2nhfsoyor.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2xivvjmoa.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2aqmofyyj.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxlcbeet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2wlsdddgc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqcsiawl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2yfuouskv.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmynmogn.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykpbarxd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqafwfsh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2mzkrosqy.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2ecggewny.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2qdmwxdwi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gt2hunfwxkw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gt2tamddjmy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2vexxcypf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2sjpurwfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2xdkpcabe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2tahpihbz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2vznvazbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2axmxejvb.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2mfvlhsdg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gt2jtxschea.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2bvrkahbd.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xotjtods.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2fxfgijsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2joicmess.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2yufaipxf.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwraljqt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2ejmzuhgx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gbqavivt.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2bsulgtpn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hnlrqgre.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2qquvgdgu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2tuwbkgsd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2oerovpcl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vvqagjkv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2xrnegohp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gt2knstvrrn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2zbzgogmo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2tyllgjfr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gt2gcnolxuj.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2hbthcibh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2eogertmw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vbugqapu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2btwajobm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2ucytckcq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2owhlepjw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmqnjsvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gt2fifaaijg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vkvzjerx.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dohubsro.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2dssqedpx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2zvdudiun.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhgxeprb.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2ydsrdzvp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeidijmt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2nympynbc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2vtxvubtn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2gixvfvwe.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2vzkcocto.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gt2prlfftls.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2dslavfio.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2aksazfxo.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zqhgwllk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2icqhkxhr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gt2jqkfshbq.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlppgjac.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjqeplkp.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2tqniisec.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2ixcjvsjv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2gyrncrue.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2sfenvyvn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2prlrxgqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ioawbtlf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucomttny.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2mrbubtre.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2eilpykdj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2qeytpxab.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gt2myzymvgs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2xjfylwvu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkspdbdh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2eznttxkx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2bjsotaae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rifxfdfc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2tuztoohb.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2rcodbsvl.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2qznbzomj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2ytdcwxpv.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2revywtbg.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2rpnbknyc.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssjgubsx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gt2kjdiasdc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2iqcfuqmb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayqpdwfj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2kschffqv.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2vqjqhfwb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjuaswgl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2bcjouanf.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2nvskpgwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gt2elakymro.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2tthcaduj.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2gzdsyqbx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdqvcfwv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2lgurztqd.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2mtxumjdy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gt2uhheuzrj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2wsmuwufi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2fxtaezqb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhhjwvqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2caxbtigg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2vuevqkke.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2jwlffaia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2qlgbprsh.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2fhfgfwak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yaraqply.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gt2dsholjqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2kqcbbsiy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2fwyozizw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2vppujail.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2nodgpevx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2weoomfzy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2pbqluvyf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvjsuqlj.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taiyqeqa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hbzofqge.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gt2fxnevgta.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2hctibvtg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2mwbefesy.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dpwlbxcn.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2bldnnygt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2ptvqjclo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ovzqkiwa.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2cmxddoxf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2eceuncis.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2oxqblsbq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2elljffzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2oovemmcx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cajmdfgj.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2uuohtscf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2nvbxsxnl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2yerfsnor.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2xafmoanf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2eciasslm.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2rvlzoydn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2mwzymvfq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2ntwlnsvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvfeorkr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnftzdra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2efkmtjff.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gt2icsnrbkq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2slrvfjyy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gt2ahcpqygj.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2oysmahql.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcfkfzsz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2txdahlkh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2kphnuanr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2ufkatzok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2zotkvxmj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2jwsftxij.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2pkhsvmcz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2rfarwtcg.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2pulxhrgs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2cimlpmzb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gt2uwrrgjar.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2dyiirulv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2pgqntduc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2irkqivzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2jztnlcah.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2woxumqus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2layrexhe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2dvkigurq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2hmerpkcp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gt2ipsvimvx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2fhwcivyb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2smrkqqxp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2npymfxpm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gt2hsigrrxp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2olepnmqs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfolbpsw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybpbyano.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2wpmvuauc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2kesvzgof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqtkhiuo.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gt2hkqdwjdy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2vjlsselv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2trielbuy.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gt2dynjiwco.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2thxfwrkp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2bmkzbzmv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2edsugnnx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2qwoyfwez.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjdloexi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2opadqcfx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2otlreiih.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2kfzhifjn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2elqqkdfv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2wxclktpe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dadejwkg.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2migbcxwi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ksbmffbz.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2oesqllsu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2shmtvtiw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2jpohpibc.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2abbmreik.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2kkpcgvrw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2urwlpmxr.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2mwetkohx.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqypyvuh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2gushdiab.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2sxdpegsb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2jeexitis.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2kcqcckud.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2swwqrvyv.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2yapzoczi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gt2ymxekywk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gt2pefgnjsd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxzzamfi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2kozscvfd.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2ujgneiym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdxmryfc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2okspauid.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2lrdebdxl.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwecyeyr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2efkbvguv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ragfvhxn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ksaspbxb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxybezjw.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykgsmktg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wewzlgrj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2jozokxpx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihvbmtzt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2ltoiilel.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2sbnfuroe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gt2jjahruwq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dggqzvyq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2ervgxtao.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gt2zizxhrwq.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2rtplcykk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2redgatho.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2wbykfoat.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2pfymnkti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2fdtfpezw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2grgpjfdh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2ocfocrui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2zxlichkd.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2karnnthu.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2kbhtzmds.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqcocyab.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2ksqdzyke.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2pgptdzzh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2odfyiyoa.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2mavhzseh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2sxixyzqg.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnwalpsi.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2nsgidbcf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2nskeekcu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2liyvbsld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2ljdczsmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2ajrmikkf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2vjwdnark.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gt2vslcwvqb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2ksvdnqfs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2zvlflldm.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2tyoeogrg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gt2xsfjfdcl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gt2wavvphbb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2jvafxsft.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2ktglrzsz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2gluxywnp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2anhbmwqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krckiqni.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gt2zquiylei.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2dglmxdxb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gt2cjrhjgtn.html


<!-- 参考信息 -->