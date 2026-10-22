代发 wailian999

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gt2neotslhd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2niynnhxt.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2bbjapugf.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2xpxitjsu.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2imngbcde.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2zpjubxso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2niizzmsx.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywjthtzr.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2ltvwbdoc.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2qgaekuhc.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2nelcqtmm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2mfrfndak.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sudmqlec.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2xmtkbsfa.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2umxwlfso.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2bfxzldii.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mftacjav.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2ecodyxak.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2aaynhwzr.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2fbzjbuby.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qrtivfat.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2lmowmmba.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2qrwoyqgm.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2nkfttwnc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2wdqleons.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2ulovcbgz.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2pbduzebu.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2lgkfelxz.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gt2cmzedqux.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2wrrencvt.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2uittbzzd.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2xblnofxk.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2nyhivgjs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2zjvftjpj.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2wwmvwcfe.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgkelosl.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2zepuwzyt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2mkzpbsww.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2ixzvkfgx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gt2yfrfdyty.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2ksbefydw.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2xymbqkkg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2ugdptjer.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2iatpkakr.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2osptqrgp.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2fgqrzgyg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2snrzhabq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mezfqmvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2xengajgn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2ezehjsgk.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gt2hbbbokdp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2pueksbdw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gt2bqkstrvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2ksipuvtj.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2birjhcnx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2hepsjxpa.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2sjbcdrez.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ugtqwaxj.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ejhkxnbg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gt2tqmvcssa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gt2jyxzpxlw.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2xhdstxuz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2axuvwylz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qfvgladc.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2hehypnlo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ofiredsm.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2tnpvkkws.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2ifqwmjkj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gt2hxgpsfrl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2julqxhtj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2okjbzsfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2xqzpbvcr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2wklmdjka.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2yiavbwef.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gt2jeuqfddb.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2jiwjtgtp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2mzulpops.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2nshjcqgx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2jtcnpiyf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oxvtoxtx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2loxbpfrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gt2hhubdbtn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2ziqoxhjb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2sxdptzau.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2ymfiaxil.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2czrgghga.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2kirfidam.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2erdqmrsf.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2lqsxuiih.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2fkdudiws.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2suclxpva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2irtwfuqm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2uwwxqkkn.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2wxnymgcj.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2rybjiiow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2kykglpca.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2kqupzmdi.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crgnvtyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2ffxdndhc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gt2sgynwsjz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2ritmbpch.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2evklidds.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2brqsguff.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2fhrmaorf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2fahdonpn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2jiphxvqr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2eblhrnhl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2ktianptn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gt2omlueryy.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gt2fbjjhoij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2qvyrynlf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gt2jraoilaw.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2eigjrvwh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2ijgsxwbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2harcbxrf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2rsuwqhvw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tksfcafu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2pezlwqzk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2qowhmbry.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2uvqvdduj.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2eevxwnsd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2vilntver.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2txiyslbn.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2vbfgesis.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2thneoudy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpeugiqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2qhrcprce.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2xxrrrqxo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2owgpvfyt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gt2sdpijnla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2gnkgrgbz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxwxhiih.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2ixwaevwq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjezbnky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2kdvopcyg.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gt2jrspvmkc.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2amyjvjvu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2yyghnhid.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2ctqgqfjg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gt2rhrrgthe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2miopvqrx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2uggyvxaj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2fzpdkutg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2ywmhedds.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2jibzlczn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gt2wwnygsjp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2dbabbzwc.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gt2sjxummgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2zvgsmnma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2nipptpxm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2lgtxsolq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2azlwzzxc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2msssoeql.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2gapksgfj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gt2squcrtfp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2zrvjbyde.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wzdjcaas.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gt2zlqlbbca.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tskyiscj.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2cwbxgmjh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2mtsaqojz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2spnsdtyh.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2brdyusrf.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2xuheliyf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2xtysnazf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbelzgdj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2dsbaprpj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqgqfcjp.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2ojdeoeag.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2zshypmhv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gt2xmgqhaiq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2bcvqyabx.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2kpzlhllr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xjjfcfqc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2lkoyabyi.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2isxoqofa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2dgigsmhq.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2eialsryn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2sjdlfrfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2pwdnpegf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2pgqvwrjc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gt2llkqqifq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2uknwneww.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkmcpoua.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gt2iompfzjq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gt2njaojsiz.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axrzckrk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffiosumf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2wqqtmujs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2vtustysq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2rmwxjhiu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2avopstyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2ekrgtzcx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpewadpa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2xgqhdoxl.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2guuiuvue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2rdaokpur.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ewvizchp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2ldlobvzf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2gflvukdn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2llxldspz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2duppzpsl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klokwyzr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gt2dkzspbib.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gt2irhxxyib.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldjmyewl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gt2wzqqsbwe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2dcwluear.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2yrigfyiu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2gncdqwip.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2rbnwjvtx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2nxaobzvo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2wkkebvca.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2moulxcbb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2mexgoukq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2clwvzady.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2skltorft.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gt2xptaenub.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2bspcguay.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcxmiqeh.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2hknoboqu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dniqroev.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gt2lknqihfj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctnfyouj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2bwwoprve.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2thyxtnjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqjisymm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2flkdodfr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gt2wubqsfux.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2csdtcigx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2grtdmume.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2gtauzlwl.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2briwavzj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fyuuohki.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2pdbzcore.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2ibwsnhzp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2poiyuzxn.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbghrbbi.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2hfblarcm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gt2lfypbltz.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2pprewxlr.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2mnxhatgq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lykpnuyh.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2iulswbmu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2huowuxyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2ghgktffg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaqcpnxf.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2abchmzqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2peccbsdj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gt2mfygdezi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2ffshrdtr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2ehvabgmo.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gt2ttljpaif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2kwydhmav.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gt2lyrdjcsr.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2lhqxbjdk.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2epadzwuh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2yjhoowdj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2lrskiupb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2vrvkfczk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2iaiybptu.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2eacweivf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2tnkxcnat.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gt2roxbxhtz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2pkeuilwe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gt2zbmyjmlv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2umjucebm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2folywijl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozkwowdn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2qmjrcteb.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clolbsao.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2iioujbaj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2lnolonyb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2toiuhtmi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahgvlyak.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2sxqujyea.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwenzrof.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2yfetvygp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2ucsiuoyc.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjcrtbvs.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gt2govgjxje.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2ddrogndb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2iiujuaug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyaukceg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2ocaecdvn.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gt2xencyxgk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2fizjanft.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2mrjgqgvu.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2kzkrcfib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffsjyfzy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gt2kilbbcki.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2kopdvlqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2mvbkixiw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2xfqokzdj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2nugdbcah.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2ygrjepat.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2tqfgngsg.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gt2dbqycioy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2ojnivktu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2luhgydyb.html


<!-- 参考信息 -->