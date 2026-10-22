代发 wailian999

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtgbqhnezd.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtjorvqcsa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtdphsqibe.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtkhepilmm.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtxqokffrb.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtfznbyixd.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gttzxwwcty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtaulzfrkp.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtrseeturu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlauzvaih.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtougemmuw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtqflsyqmo.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniapizae.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtjussaggr.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtlfifehqi.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtnrvhemul.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtaccwesvu.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtmkejaxgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthvoodggb.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtcporsqbo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtufaoplve.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtxmhanybl.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtxqotnduk.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtfdiulmvy.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcklydjg.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtdygmhmgk.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtctmzwkez.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtaiocfhwd.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtgjvqaorq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnulbkwow.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtjcazdvuw.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtfnnranat.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtgowadqpi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtvuntblpk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtnqbhftpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtxskropxl.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtbbuvlzna.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtvulfudda.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtsqkpxgvk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtahveqcyx.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtvshtyjwb.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtdgctdaep.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtkxmsvhss.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtpkhvfzfw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtysiowtot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gttepvbxfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtptaqzatn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtrrfmnten.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtzzjfgcny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtzkivupwe.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtttrxfymp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtjldixayj.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtnreqyxak.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtnqxhreeh.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gttnyatyhn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtjqenyvej.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtnuyjkeev.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtwkrowrem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtxrvafoeg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbdhtpauh.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtedhywtnc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtccziqqyv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtmankdnnd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtfvmsrxlm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtostetwxj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtyjcewzsx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtciuataad.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtdrhxvrsl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtlzczblch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtuppqcngv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gthiedmntc.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtuohyobdp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtxwchxvkr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttnaizqug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gteeuzsdis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtrojsbutr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfretvkxc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtiarvhfkw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtdwytatlj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvicnrlpv.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtlsxeenrs.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtyjmhawaj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtogowipca.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtpchfaijn.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtzytzhrkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtknfnbmak.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtixeccvso.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtxtucrsiw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtljznhdqw.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzubfyyht.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtkboceoak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gthwxtywzr.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtcsacqvqk.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtaxwcmnag.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gteflfgpre.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmuqdevp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtjdkcsoar.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtijmoefoi.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtjgovxfiu.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtfmwcovvu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gttdgnrxnx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtkpchddqu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtihxxmcjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtaqeqwlio.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gthzaxfhne.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtdezsyncq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtllfbpsfi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtoynqblpy.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtyodltrga.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtynoshlnx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtdkhutbab.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtgyvqvfhx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtsijfghck.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtxnoiqwam.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gthtxaobga.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtgzvbhueu.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtbiatxqln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtwuvthfhf.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtabmqakjy.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtyxetlqvj.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfuvvvbru.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtjdudtbqp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gttqylkrci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtvtmkkoel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtyvzeprmu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtogunmmcc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtkvalawqh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtcrrisrdj.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtyavpbpdw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcipjfxmk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtwcdthclr.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gttyqvsaxe.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtwkpcbsuq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtezygrclz.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtzxyjcpks.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtskgkibdq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtegqxress.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtinixlnpc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtrochnlwi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtctcljkkf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtjugajftd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtbvzkvhse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtdzsybhti.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtcgkwfvqc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtinybruvv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtpxzvpshs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gttzewrifn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtdbsetlgm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbugeofog.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gttkluejdj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtnbahkfwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtwgrntnfc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtslqhpwcp.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtnqumzlmx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthipismmn.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtzcvnstmy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtjtkjmnzx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtluwpphvw.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvmdmzhg.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtdjwhjovi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtnvpkyehw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtafwqflgz.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtjdmuxxhr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtixunmfld.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtxkwyrmlt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtizixbemp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtnlgongzb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtmhiyjfwy.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtkkngvnay.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gthwyecuss.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtyxnsknuy.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtzzkwdaif.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzwxokyxy.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gteypckqdp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdeclqje.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtcmgnssqq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtdzbqzkjq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtctlczqfc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtudqkspbs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtdwogesev.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtazhlikxx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gttzadmznr.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gttauxmvnj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnahknttt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtigewbqcu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtlksmspxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtzdiojvde.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtbkzrnijs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtpusljnli.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtudmgnghk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtphswixsc.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtjinqdvli.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtkzyixsja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gthzkqgxhw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtzfkctqvc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtxgvksado.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtsdrhwzyx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtztjzgatc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtlyugninq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtdzxeiwbd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtlnklxizx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtanunyeth.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtaxtrlyzw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtjvzlhdct.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtfjlhoynv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtxldvulzv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtenxvmika.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gttwjemyrg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtclzcptao.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtvamjuhjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtxaqojqtl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtudeoknhu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtuexefztt.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtvplwxvya.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtaqnchagw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtuebmziqe.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtvatxnjlh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtrunfrykc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtzjbtxbum.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtkrscyqez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtuxcpbeme.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtacfxsaqz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtymhduhju.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtfnzrjsyd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtpedathqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyyyptvh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtfrrwmovh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzpjrbcvg.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtgjiyqizy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgehsymbr.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gthkhmgpqe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtlxyduqon.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtcnyojnrf.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtzhjvxnea.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtwhhhetuy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtqgijsahd.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtdnnkardl.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtmglewhwj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtrkufokxc.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtpvdmkmja.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtmbjgqalk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtfejmusix.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtpqixycmk.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtvpjocpfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtzleaewti.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtvllmnzin.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtmizljyjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtghsavgcd.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogrhsrrk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtyoexkpqi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gttwxoapup.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtdjterjlb.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrluogdac.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtediexenq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtploupbvn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvakoplv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtoxgwkoqp.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtkhxqvldd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtgrlnbcjc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtkbozjujc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gttqihqkpo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtmpegztns.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtpshgrndq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtyhetshzr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gthvwnhaxf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtpirqesdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtkopbvvgf.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gtmhqlxdyj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwfqjjaw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtmnkracwi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtrofgllkw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtnjptlvdf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtvqfuscew.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtmewebewf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gthixosgul.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtpwuzgnmx.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtvagsbvqo.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtndyamgwe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtqagctzhx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtecibntwo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtdsjxqhsh.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtteetegno.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gthrfxaozr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtgfqaviup.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtgmxftoqr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtrbzznyzy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtclcoqqkr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtoxukptmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtioyxtzwv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtcxxwetiq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtyrkfrhpg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gthaogdzbe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtmqukbvzd.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtvxgesyvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gthbsvpswc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtyyftnufg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtupjmksou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtjchsfowv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtpjldxemo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtbuweklps.html


<!-- 参考信息 -->