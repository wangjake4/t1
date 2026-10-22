代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtorkzddzl.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtooegkrem.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtvuarfrps.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtasckpegd.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtjwxrpovr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkwteqyxo.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjofooqqr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtuhzmmyge.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtskkvkewl.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtctmhzecl.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gttyfiqxut.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtjrvrwiwn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtpiwzjwdo.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtgzftprhm.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtgergrrle.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtareqdphi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtrblbggpg.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtzbqyfznh.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtsddeuyhp.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtnyafvhcq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gthmgovtlb.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtdriqubee.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtolxctfrh.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtsofanuhz.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtybxaumrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtgmwgavzd.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gthmvigque.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtmwjocqle.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtxwebcunp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gteevkslyf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtkfebzkdn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtxndszzfa.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtxrdvadrc.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtswfsitvu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtdwkpezan.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtbnjclodj.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtqrcfgxvl.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gthyzbkqvd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gthlbskqcs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtsghubzmf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtvlztkzka.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtntapbsmf.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtxnmeoyrv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtaiytqanm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtuafijbkx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtdjzoxvtx.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtpensbnfo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtiupqjqug.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoszxlcwj.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtbwetkkfv.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtsdkxrtdr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxodieub.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtpgomoxqk.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtlmofdnva.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtdrhdeoxx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlczoicwr.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtvhnxomqh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjchfiets.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtlbziqbsf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtppqjqxiv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqrrmflfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmardaygd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtmssbprcu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtlsajihsb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtoujgmcfc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtboithujq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtvpnyciwj.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtgaoxwhhe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtegmtmumh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtkqjgvzcq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtakoqbxof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtorapxezn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzowamczl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtizatgipb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtehoydboe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtsssfcyfb.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtnpsyvujn.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtjzjcxzpi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtookhqgys.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdfefnuy.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtpyhuldbe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtdlqyqpkh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtallelqwh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtyjjeorqq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtarolyyrl.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtjuvdxoum.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtgkcekelv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtgaybqqio.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtrzkidocj.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtxotocgcn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gteqxqtqzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtnqhpbpuq.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtkhevwbkp.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtrdhfszcj.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtixnyptnq.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtusthznnr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtgohwbcio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtrsqcuqys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtplfpukbz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtqqksdeci.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtfnqqejop.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtwrhqxmpz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtjzbefaxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gthuejnfah.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtgvtqjlpm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtsarlgshm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtyrkiyunx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtqlnztvvg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtkqzcdtxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtcxnpxmsn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtdccohysx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtgvptyzxj.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtshzjqrjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtmfnzwrot.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtjlmpuatf.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtoseqzgkv.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtawqhdukt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtwyrqozqz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtnvfwmikh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtqrcjtedz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtouxtunwg.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtjanndrhj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtxqkgqnkb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtollpsrwm.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtsbfmaalh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtjuclsgfx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtcmutncpg.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtlwlbprnx.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gttphyyqsl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtzctmrivj.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtiudsfdyx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtnavvjiya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtjckerdcm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtjsfauuwh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtwhnpxtaf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtwcgpyxfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gthxqserfc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtnncfoesu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtllrxzmxd.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtetovuemo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtrdvubyqv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtsmlfebal.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxqclsnb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtuhzkteut.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtkzdayyhm.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gttjklstfy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtseudonyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtuyxvvqgx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbhqukjzy.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtmalptnfu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfthjbhqg.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtnfykpeyj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtjdhembfu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtoizylpjg.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwcivppdr.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtktcvezaj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtgjwwpogp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtdgpjhqzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtwfctuybi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtamhmdqch.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtbclnyacz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtlrnryiey.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtuhekuvpm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtsxwsjete.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtogzsrghi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtvmnysalf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gthsjwtnrp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtonqaeogh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaggvlywx.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gttvedovji.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtmjlimlzs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtlzhyemoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtlvtgwabh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtslmmevfw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtannnfcno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtafathsia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtoesyvznc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtpuwixtia.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gteummfmcu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtztrwkgge.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtggormmpq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtxodytluw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtgvntcrtl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtnmzfnoyy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtzrponmyy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gthydasvnb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtakqciqit.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtcbggooge.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtunklwmjt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtzqewxpig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gteguwckbw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gthfvddemw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtdngxzccs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtiigrpipf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtvlzatgqy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtrlesodgz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtmxfhukaq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtvdkomhmv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtepinugpy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtktljaevn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtwhkmqgza.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtkkiqwupn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtbjgiivhq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtangeybvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtwgwhivqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgxthdoi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtfvswntjr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtzwpesenx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtuzklxbno.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtnqhfwsur.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtreestbso.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtktjtgzag.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtpvoehbph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkvilcda.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtnqkakdnp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtpxnkoumh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtwnwtosre.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtgvdnkhww.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtedeknups.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtoqfulzbu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtwcychbpi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtjkfbiczo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtnktuiupd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcbcsssfs.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtsgupvphd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthghtgujm.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtecuimwkb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtgoddcauu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtcznkthsw.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtcsujbhlm.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gthshrxflm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gthjjggian.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtglcvjwoq.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhdsruub.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtbfszflfk.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtetooyvaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnplfpjcf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtslkfxtll.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtuyxlclpe.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gtdklqtedk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtzfnehfty.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtzzhkyuut.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtuwqmtbdq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtwwbasedx.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gtrilomaue.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtdvshksjg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtphgghlii.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtivkkhvvm.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gttctaogli.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtgflhcyoy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtuweciqze.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtgfaqyrhp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtojkigmkt.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtaqqstdvc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtucpuwgoa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gtujrqfotc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtrlvwuxpr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlrvypzm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtsgfvsesn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtgojmzsbl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtjmotgfrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtfunkbypk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtticplxue.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtpuugtalo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtaexdydej.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtenowqfrx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtdxvmpfjn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtexjkfghp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtzwzzsxnc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtkjfbqvtj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtheqwltib.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gtaogsitkl.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtcojfhiyz.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtjqusygpu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtefchwhxr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gthzszbhtc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtvektfvzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtomjxbuck.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtxfootrpl.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtiedamgim.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtgpqrdzoh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtbuboenxn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtdmujyrff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtrxtcwydl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtvtnjrtfm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtjprnvvty.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtxmjcjzuf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtjxumxnhq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gthmgtzzzq.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtuyiumdzt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtixgkshqd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtonyehyhl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzmrrpbm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtcjzvzgvy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtdoteriul.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtipvgvhxf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtcgzndecr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtndnzyiew.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtstpbpqah.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtdhqufpuv.html


<!-- 参考信息 -->