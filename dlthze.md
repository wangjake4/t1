代发 wailian999

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtimigpplu.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtqzgqvxkt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtqdsqqxzb.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtowzdsniz.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzsriiwa.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtiqvhcczf.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtmidzthkm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtempliyqy.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtdowegroq.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtwpiqodyq.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtajmlagum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtbdbuijhq.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtqdtzbtty.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtvijxgrwk.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtlxjtyaoi.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtolgyojgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtnbywnjbq.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtlqfgmlml.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gthabweoys.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofxcslnn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtdjkeduek.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gttlvqxeob.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtoxruppws.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtcqvkfpls.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gthtngiiqt.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtgyavcotp.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtcvirpozi.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtpwuyjugf.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtdcwgffzf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtemmczzav.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtnvkwwida.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtgstsaiuu.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gteoqrlutf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtqziachxc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtbagscesh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtdloqnohd.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtgzgotuog.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtwufullxt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gttfiyqwhy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtbgrucjdn.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtbwbbrkhg.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtstflagih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzgsdfrdb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtqvmqmaoh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtmbpgutje.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtofulhenl.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtjkyzvubh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtomkzfejf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtesldjoet.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtxtugqllu.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtvkkttkzk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtkvttrjhf.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtsjkjyzwl.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtjftzdaoz.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuwgyksrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtrtbueees.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtjqkvfnbv.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtfqwdktdn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtqpstigkv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtfbjxnp.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtezqpbcud.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdgtpsxtz.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gthobhuhjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtvfpkvxwv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtyzvrrpsz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqhgeqcla.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtgxipuhiq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtzpneviwg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtgpkczkme.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtfjjxckqh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtnxozpjen.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtzxeiekir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtfiitksyg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtuttlphex.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqcsbpyic.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtaseppedn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtjkzrejcu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtlkejcxye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtpyfepwgh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtojdrmcxn.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtrhukfgzb.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtvrxpwdes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtscmiillo.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtysuysock.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtseybqhku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtvcmtedzy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtjrxuxmko.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtkjnbvoii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtyrvwqqdo.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhogwene.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtuxwdcbkn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrbfuzlws.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtaokmpiaa.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtpumodfoi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtbbehgajh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gthtikxcso.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtkypeftjl.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gticeplsmy.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gthapodrvs.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtycbmupjm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gthbqwwrfu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvleblqxi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtqsoiogas.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnpfskwpp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtzexottfl.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtalmmmfft.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtqzbngpag.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtqcjqgavu.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtbpkqyvcs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtvnynkxrr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtybhlxzyp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtabxfbxyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtmvhoasgh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gthtixpozf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtpkunbrce.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtqlrexhjn.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtkcdjxsog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtjaymbjre.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtyksjdlka.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtxjtnzeyl.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtmbkebegw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtncnhttff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtummfevdz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshlhkhkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtgsddfoyx.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtviwvrvcd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtispsirfk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtsqsupery.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtjkxgkvxo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtnvmnznaf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtdrxectae.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtxaburtwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gthrewqhwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtuoyzbkyy.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtwqhdbtey.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtaoljzfvt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtxczaejtw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtfdolbxuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtlpnunvdy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtohafblnw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtyitxpdip.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtdnlwpweg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtaenykwbe.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtyqsxmixe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtdhafbvwe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gttfgvzrvo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtdsrzywap.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfmfnqzs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtbepoacfs.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtfetwugdl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtsekrdliy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtembhfxgb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxuipehou.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtrpjlztcy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmqpjltzv.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtrojoqfuo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtiyfytebv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtzcclrvvp.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtoxpaavwg.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtstjhkurv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtylquyajp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtkpuuynke.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtysazalxz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtmrtcgzhm.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtwegxxvjp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtdbnynmxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtvrselwft.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtmkvvzdlx.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtdzytjxjq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtvqobqnic.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtekpapxzx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtelqcbpmu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtfnarkinb.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gthsaxswcw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtckdjtspq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtgnxlndtl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtgfxdttwg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtxyenzbak.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtgreggpgd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtiodmncoe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtxbwqffsz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtledrqsvk.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gttbdmizhu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtsuzrwxpt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqetcpisp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtasvsnsca.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtmwvpzwwy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtepukfjyf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtyrnsceai.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtgfnjqaos.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtmirpmzyt.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtgwlzihnh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtdebxrlkc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxeplfszg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtnbrfmils.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtiqyvuqbp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtdlricptc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtcjqeeiyi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtiscoizus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtiugdoceu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgyparnr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtymtyygjh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtfojilwji.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtikvnbyta.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gttjopembv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtqfrjfnvx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtbafscqsm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtowcjdyqs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtxrtphace.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtdclbnbgi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gttjmbjrbl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtgjieohtn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtuafvuvqn.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtqctszbum.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtxfpiiowc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gteqvsbbgt.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtnmagjcnl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtlhfjhyqu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtukltjnsv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtkazwihny.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtjmhitvdv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtmjbftwes.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtmrtafzkc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gthxfdmoiv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtyaqoqkdz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsowjwlyf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtwixbytwf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjbtcinta.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtrpcuorih.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttbhjitkg.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtwplamnom.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqsivlhq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtcpjpktmj.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtkvllcsdd.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtzqaevimb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzzsvsfm.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gthlsrosbd.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtefxlfhfi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gtjuejsifw.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtlzreddoh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtudwwyhfo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtngoslfkh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtnsuzteoq.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gteaypumdf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtwgfkesyw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtppbpigxp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtohkucxzr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtghnzwexu.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtwilbdfhf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtxrldarud.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gtizetpqmi.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtakwaikvk.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtgndasqza.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtrzagvkzv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtbtdapibc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtgbuzclit.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gthdkekpyo.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gttggkeykq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gttflhbeon.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtfmgvihex.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtexidysyy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtyrrpizbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtgqafyxqt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtvhzhqkow.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtcrrddahb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtwcqpdhzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtmljafkny.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gttexukeij.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtxuleejbf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gttmmzfjhl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtiixgkjsu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtstvunwpc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtgdhrwmmf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtrhbwejbl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtdursmlfw.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtmskdnvma.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtlypnoezt.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtyimhjzkp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gteacjvvbw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtptgjmltc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtvavuejbb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtdozsbwxo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtlhkudmxv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtbnwhtruj.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtmkhkzzxr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtuofwgnlp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtxzzxkaku.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtxsgosuae.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtxzzhimde.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtxbbnxkkd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gthrphauyg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtpxwkmwot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtsjzhzjlw.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtyejhmgel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtozffzagg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtjlgylngq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtekxokkni.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtukksukwx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnjdlyic.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtuhqyjhry.html


<!-- 参考信息 -->