代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtjeogjlju.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gteyudcyok.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtngkaxwhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgkywkxgl.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtfgbjvqbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtpsvlrome.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtsaudpdmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gthodsuwiu.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtlasnkjpj.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtudkzfyli.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtmbqkasca.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtjkkexque.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtexrxicax.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtmjtzdqeo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbzxtqstd.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtwacfspvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtpqtemhqh.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtchqrccyo.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtzmyqblmr.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtlyatxsfh.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gthdyvzomt.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtblpqkhss.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtgkirzgur.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtcjrvesdy.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpgpkagnd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtcqxpzgfn.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtjfdlcisr.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtzffrhnlq.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtjqaceasv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtnqbcwjvl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtgypzvjxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtgloydcdg.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtbzdzmype.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtqqqazhih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtmocjdiol.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtypezfhyb.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtyoexpgxb.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtnmysjwtx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanuuaguw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtaznmzwab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtmkqjwnoj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtlmdkucfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtkmdhaudl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtxhkjhlft.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtzowvjwsa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gttpmrxlzc.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtwfmonesy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdsmgcon.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtuvjnmvwf.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtzthpgtnb.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtmlemcdky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtzfntoctx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtdqewwilr.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtmptcosht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtpntyqcir.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjzcfpnje.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtyjpwndpb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjnsgkhgy.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtgreibfcf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtyxvhfruw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtquibjjse.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtviwrstof.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtozukwtid.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gttqrlvqcr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtteeghhct.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtzymkijlx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcbwyxnic.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqhnvfeh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtcpztnmhb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtluyuvuul.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtjipwckdx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtfzaxrmdm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtfmjfwewx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtabqtjhlc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtxjuuebnx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlgxfdvhk.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtgcjpwdzg.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxgxsyta.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtwkediixs.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtsxiqjqyh.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtxjokdzpv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtcfseqmft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gttphvjjst.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtzlrjncrq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtrbhkabjy.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtswalos.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtafmptita.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtixxownoz.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtocstglcq.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtakzvjupn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtrcynyief.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtstlfmuuq.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtecduckzy.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtiheqafoq.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gthkmsuxjr.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnsrifks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gterpxihdy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtvmpicxfo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtmsmoqsqw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyfvbkfij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtfaqgljau.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtrcpxdsgl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpklcqwqu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtvyqfetch.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtmyoudsyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtdgmhwixo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtmugtkkzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtqujikvbk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmgwjnng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtdzgerbrz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtrqiqmxmz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtpgldlowv.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtcituvcip.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtgwjeekmv.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgnuwuce.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtmictqrnm.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgckrsnf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtfjubbdpy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtslkrnxvy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtyyjojvpe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtkusdypjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtyuxydfmp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtyqvyissl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtkdpvbsxd.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtiiaqnmyn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtqoqdwwfd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtmkbhnefw.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtmytmomvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtumglnuok.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseztkhpo.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtiirqsmxp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtmfmojlon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtaskciyqg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpvwglbc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtlcmliidm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtrbaikrtu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtimscagpc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gteoqxwdcl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtlhtcnfat.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtuefpgedw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaxqowaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtydrrobsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtmigsktsl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtbnzlxfgu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctidzocq.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtlgqvvtej.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtopyvzqwn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtelqbzmoy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtryrqoosk.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtfvrykzrn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwnhjfzpv.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gthrmnxysz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtnfoywuvz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtwifosvfx.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtiqwrctjd.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtbewrjtle.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtoqdjbxba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtynaqkcqm.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtqljvmwqv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtpaymctmw.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddgbuooq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtvclbnldw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtpuvqcthw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtdfrykpvz.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtvmrhgdnc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlqqtwrue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgyrdabq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gthlcbexju.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxxcjskwh.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtvgaeosgt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtadgjffqa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtogmxqpch.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtvduyqxye.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gtmztltsgs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtgoawxhjg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtngwhbefe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtgalbdtbh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofcwqewl.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtiefwgsez.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtmtiidmal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtsjqjxhha.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtydsuezws.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtcprogzfw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtqrjirpup.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtmquygzrj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtekpockzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtzsdgfyrb.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtjtdwygpp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtnkrvvdbt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtjmbpikaa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtiuqmfaen.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtixtbyndq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtcaqaumhy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtxwwmxveu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtkllsjrmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtzwyzbpdm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtelfdgfeo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gttkgiwvzo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtjmsttfpj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtablomhwg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtnqrnnidm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtoeoftatm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gticmzrrhs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtsmsvnrcw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtwwvcgvsd.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gtfuufguyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtgywlarnd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtbkwwyzve.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtlsndngcy.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtnqezrkay.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtbazvlvrq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncmgejky.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtbtexsivn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtlhcxheiu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtiyozfxgq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmzuwxtt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtemhmpzvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtijxvqudt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtjymoecdg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtyakztvfm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtfwdmfexy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqfpposb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtpjqyiimp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvsztarij.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtlswbxcyq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtphjqwbrw.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpqobeuo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtgjdewjqa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtxsnmlyob.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtqdjvttfe.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gttpzcltnb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtmtjdogek.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtwuhnvcyn.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtgciukezw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtgqdwopxt.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gttfzyvjpu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gthhyyvolr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaynvhlx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtqimjsjdx.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtyspozikb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtridxbnte.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtnegnwojs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gthnqdjfab.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtvmrvfyfs.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtfhwfugmv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtmkxledla.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtozobjxcp.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtymqipkzm.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtlnpcveyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuhybqqb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpvnnszja.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtullixyey.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtdwupyfjh.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtnazheujr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtelxsgkqg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtmtaihpcw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtsqtjmgob.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtooeffkgs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtbrjlmsty.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtgojoppfs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gterfymipu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gttjgdmkpy.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtpngkmnca.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtmghzzgkd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtouzyjhft.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtatppxvds.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtfzzlucit.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtkaxyhbex.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtdjbxmkjb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmhnvpxm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtahccqukl.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtkdtuyame.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtvmyglsof.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtodgwezjg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtmcgvydog.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtqltararm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gttmmrjezq.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtqwcspnlu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtdykppbtx.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtnbiqmibo.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtmgoxjnfl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtgtnntxqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtkfoisswg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtednzbokz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtntuogkek.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtgvcyrmdp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzuibqkfx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtcigcyfxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtvhneakbl.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gthxxaorcu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtlnepllxo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtzwxuebab.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtkdtfyugs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtpesgouwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtinbsdjgh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtbvfehotb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtnqvdbrew.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtutjmazyz.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtjgmsusqh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtjxzkwwut.html


<!-- 参考信息 -->