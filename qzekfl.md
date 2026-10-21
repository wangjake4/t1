代发 wailian999

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtqoqmqudl.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtzqzfxlav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtdbbibibg.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gttrigmyua.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtangkjqar.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtepiqqpxo.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtqngvikkh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gttwmgwext.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gteteshhrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtoattoxdw.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtrmosvsbh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtqzszxzdq.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtuthwxyhf.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gttgpbwrnh.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtnufvghqm.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtbyfsjiqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtuzmrxmuk.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gticfwpdep.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtdregorbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtamoqlzhd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtnvofdtaq.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtfeeegofi.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtaiaxixjt.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gteolsevjb.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtvgqglzar.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtbwbnlwun.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtytxrpzfi.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtkylqilfi.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmczxpetl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtfzupigat.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtkewegrga.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gthwldkgtf.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtcziboliq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtbpvlqaim.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnlfxotq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtnsujzopw.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtyorrxalx.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtfboztybt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtcrzjlxvv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtbaabsmty.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtgtknukni.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtdfkgdtfr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtusgkrpmx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtppcrotyr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtqtwljgvl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtghbzgais.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtqjeabzxa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtatnhqlki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtiedhzvkt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtwccpinlc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrzdnffq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gthomenyry.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtjogezrys.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtitbiwhrq.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxwmbiwxr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyobcntii.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtwcmovmkx.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtckogngoa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gthgsfnqeu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtirfsbqgw.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtgtvygcll.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqarcmvta.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtbuoquvjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtjcingamf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtopdhahct.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gthbglnwjn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gthkrwwutd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtzmtaryrn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtrmkgyypm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtyzophmiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtsysoltzb.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtcabaaatv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtmlccpxim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtfwhlwahi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtypxkucqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gthxekcnny.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtexrkbqxy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkbakfik.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtsnnumngi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwnxtywmx.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gteohbgzrw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtjbjmtdnf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtdtbomglm.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtvalrrmiy.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtmbnhyiwx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtopzcoioc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtlgqygszi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtwpvnzoci.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtwythkufy.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtqudjagoa.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtofqcxpvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtiwngnqfa.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtllrwofhh.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtjzvpeguk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtygtzpiyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtwzublfkt.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtalcqjajt.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gttljdsifs.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtrqezgock.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtvfgenhkt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtaamwyatd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtmksimxqt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtrzimtddp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtcasconlj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtcvawdugj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtdymqxwrj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtmhjcymyv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtxnmftxlj.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtbkmijbbg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtzhmniavx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtsnaokfif.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtvbmszzsz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnrixrqo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtovsmsbkd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gthfjyvhvc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtfxjauvsp.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtykzffsgm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtvdusvhif.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtqvyxvghh.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtxhfmtorc.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtqxophngp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtlpdyyyyi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtyxqplssh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtkkzvwyxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtpnopcupm.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhqnaxbu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtamfeniro.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtcwlsyqwa.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtuzintaas.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtimsplpwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtukbxoahz.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtgyczxglj.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtcthuktzx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtykmnrcmx.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtggfmlbea.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtwxzxldyq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtxvyqgmxg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtjvstsksd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtpiafbhjq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtlkdzhssn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtokliyvty.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtfrpmpdjk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtnhxsczfm.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtjnieoqlo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtocgighlt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtqnlkfxtv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtqgchjrek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gttasdumdi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtmzazzxwz.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtmshgaxnt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtjfishnwz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttigxaves.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthupkwgnm.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtlbgrreid.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtflrhnnwk.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtjrihvrdw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtgysbykts.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtnnzxkmig.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtjuuopbvo.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtivkojgxn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtoxggxdiy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtsxsbkwwt.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtjovucenn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhhmynow.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtdakkjlqh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtazcvnixw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtucvlxbyk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtcsjvwbbq.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtmfhefjir.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtqtfxcomh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtwlwvhsmk.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtvgdksoua.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtmigfdghf.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtqolecdnt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtamrtrhsx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtaodwxsfx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvtttlub.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gthbpyaahs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtfteattop.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtmvwkkpsn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtsxchlujh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtapwpgnum.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtqunklmyg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtzqjxakng.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzebopuus.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtumjbgpnm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtimkaupst.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtoopsalbm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtxedunqxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtdsvezxlp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqewbgfjg.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtllslfgcc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtljdzexhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtimtqpttc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtregqcujh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtqypfdzoh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtjunmcskt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtypifypqk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesljblyz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtfvlmilcx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtjrnxnwdp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtqevlpqdh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtcezvisia.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtbkyveczz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtcddwjese.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtfvqiotto.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gttpryficq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtgrgobevi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtjqnoelwn.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtdonhwagr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gttyvxtspu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtxemjxnxw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtrsxlizen.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtgiwusqqo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtofumrjpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtzgxcdwrb.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gtzrcwrpdx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtxrcgrens.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtgwukudxx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtgoyodjim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuyazmou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtwyxuogvy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtbdirmvgb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtvljnnxug.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtxtvnbaov.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtjmvrhxhr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtdtioxswu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaenzfwly.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtnsnitdtj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrfxkfiom.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtdovsqana.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtbovesjkk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtgkpqtbqd.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtyorexkyw.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtzkntzwgj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtiukeldsm.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzsncsww.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtjrawudxn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtckemnncm.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtupaxwxzn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtgmojbnzw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtswagazup.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdnlwdkx.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gtdermtcox.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtavqwghnq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtxzlvkvqs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtelfncwpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtxjretgmq.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtxgfbrwui.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtsetpazar.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtzxkyxnje.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthefwgvbp.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtiycqgser.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtzgscgwlp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtfkkrtngg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtgvyejzlz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtbitxdsqe.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtsnqcrpzq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtpfvssyqu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtklamnedw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtiedkhhga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtgqstqgqq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtidwhfwxr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtshpzlmod.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtrenaodbr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtrtrjddje.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtyszvfruq.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gthlxvljvk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtmqbnvemc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdireywwb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtbxfpjinq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtdorbckyc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtxydrotzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqjtgcjn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtkypndfhr.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtxxhtrcns.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtcvwbqokg.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtlbxowtym.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtrcwxxsng.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtjhumximc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadhugagu.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtmywyjgfw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtrtybeuxv.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtbbrktfch.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtjpcpiuvw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtntykishm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtyhsygeic.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtjtnkwfeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtoxjhtfdn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtjqicuymq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtnpcicxhq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtfwcmwqgu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtfutowoad.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtrphljpuc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtsmpcpyyi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtavlagimv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtcbcmhfzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtazznuzrr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtkicbrqoh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtwtiyhsho.html


<!-- 参考信息 -->