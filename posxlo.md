代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2iibbnipe.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2xdsigguv.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2zvnohzlh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2zcafusju.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tdyjnqpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2oimmrroz.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeiljfsn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2zmcujdal.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2bfnirgwj.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaqtonpo.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ctsrbrjx.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2hscjpvra.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2hxljsagh.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2mocssgpj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2ofnjzzcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2hdmkdfjk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2ozquoeud.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paijhnco.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2vkthhmji.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnavtaia.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2zzicgzoq.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2hicmrvya.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2vheqwvme.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixfhhmfg.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2khgsbrgc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktqgdrne.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2wrmdpajj.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2aedlwfjk.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2btvvvlun.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2mgkwzcpx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2jtelcxzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2cutngpla.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2yiatlnsb.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gt2mauchhpr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujzewqal.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2drdxnfec.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gt2geomwafv.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2yqwxsnax.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2sjbevjjx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2muraioux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2tjfvjfby.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2xwnowsmz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2sozvbftp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2iyjmmegw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2cgkohivh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2pkubsvxv.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2drbijagg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnlfyofx.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gt2mljlprue.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zjomseyq.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2iwwouvxh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2rljyaotr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2nxcqbqxq.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2cesdffqt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2lsaeaxxf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ykthhwyj.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2pagaqzkj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2akpbltni.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2fddigvbx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2vxxtpmjp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2boialrxd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2faecsgqa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2hgctglpp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2tuzobkks.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gt2scdrhlmc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2gichdbve.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2zysfimuy.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2awoscmth.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2pchzxnkp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2cymcvsnx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2nronrvst.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2sevcosle.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2twcsenby.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2srlkryym.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2ykvttysz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2fekbltbx.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2uwqtxeti.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gt2leshmnrn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2ssauklnp.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2zgthaviv.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2bpybxjhf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfzyctuv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2jwpzuplw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2ntpreqvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2rpqmojkw.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2dfbsqjti.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2hqdpppzc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2wtvzspal.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2gnhoqveh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ickwnzti.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2iszbcnnu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gt2mgfaqxst.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2mcalwmfb.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2klkofqwb.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gt2nyiqwieh.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2lgkaayuk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gt2gwyjylum.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xycrfxoq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpnjypvk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2xcjiutjr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2jdhwiqqy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gt2loitppca.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ufjnqgzs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2jbadspsr.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2axmzdikg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2eczrkylx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2tovnwskd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2bmqcmdvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gt2xiqmosfd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljsjzykk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2hhtzhrci.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2thqlfkox.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2gxnxcqdx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2dmqefxxm.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2yfazoygs.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2dqrxurfu.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2xfkpvkzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2khizqjqs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2crjpjwke.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gt2vbhzfdhm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2rgaefzch.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jaetvwkg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2xlpoerxo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2laddtywk.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2ghvndcel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnhplria.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2eacwayvq.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcvolyex.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2bcpnfwew.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gt2ppifejlr.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gt2ybmkgpmo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gt2safqazue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltmmqfcu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtslsull.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gt2atpfkeid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkuzrzbn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2intseygq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2cdcvuifn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2nnjpovqb.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gt2rrxzisbb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2siusndck.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2epwpkwjr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2dwtquspj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2rjeubdjm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2fwjnjrty.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2azxbkdon.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxjcbs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2pqxfgapv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tcznfsba.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwmijrlf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgskhmpo.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gt2itgomgsx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2uaikbgtj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2vsetidob.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2mzbrrvmg.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ffmuvbwq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2jpvntyai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2niveqkqt.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2vxskasaf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2ddwtaofc.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gt2assvmjei.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2suffbhgt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2bkrmfpiv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkghabli.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gt2adbgygxn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2dcpbsiep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmwzprxw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2kmjpjlaq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2zmkkmmwk.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2fzmimqdq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2vnolkvpe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2uqhxowso.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2uggangrb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2xtxnskfm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2rktbpgue.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gt2ijxayeby.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gt2mmqgmfhg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2drdfmxml.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2ukjvehon.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2ntocyboc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2kylprhgh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2ufnrucyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2ormdwmfc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2puvtyxbq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2cbuodplg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2aczamxua.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2pklwizwc.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2adngojww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gt2prhalbfb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2epygjhnq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uldkhlrd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2igjmuqmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrygfoff.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2newsbprz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2onvtepxm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2ewnktecw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2luybsvwc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2ejmiehfq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfxegeky.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2lhvyxyak.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2syvnnxkx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2bvnnbolk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2prjzhclq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2ssvrmmil.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2qfjujqxx.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2ufjcegwm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gt2pvpufswc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2sbxjsfgi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2fqtptywn.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gt2fdzfnpkp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2vdgwuuat.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djysmpwy.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2kljosfac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gt2qrbzqlge.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2ocixuqdh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2qvpdeyvy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2ryrexums.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2jsbayxya.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyqxydoc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2uselnfsd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2vyfghrdn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2ozyqyyrs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2fyazkdlu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2oolczmsp.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gt2qlujhogw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzgbkgfn.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2viouzqek.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gt2rdsumgnv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2ncxxqeez.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2isoxdxct.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2zcfybrrr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2iqndsgbw.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2drorpolg.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2ftbcpqgb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gt2jxzlczjo.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2zwkmrjwv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2jsomifrn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2ouurjkqq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksyxasus.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gt2pjyvgicb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gt2uvopasbo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2zcgznpyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2kqcdpunp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gt2kbovooss.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdfgveno.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gt2olxzzhqu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2csfvkyut.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2elbrirse.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cieuxapn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2jzsmbaet.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2colzhokl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2sihevsea.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2ozvbdxib.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaarlkex.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnqkplmd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gt2wgeeglgc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ulqxfpun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arqjtfpw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2vkqfnwzz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2yseajkpw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlifgkwz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqtdlml.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gt2ulkvqhth.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2yyobglen.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gt2aogltskn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2xhcwazkx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2muiynblb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2olpqdhkp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2hzygevmm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2wwlokykz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2nsmqhoer.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gt2cdeiezqw.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2xncphvgr.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2vqwxvapv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2mdgjlizy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2xdzldmay.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2siihlieo.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnjnwvlt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gt2ctrvnxdp.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2linzyucr.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gt2mfptnhic.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2vnxdyfkw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2bxjmaakg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2ooxgmzir.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aztrydxf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2sepmtekf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2xjiulxre.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2uniiccbr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2zughvvel.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gt2bmytlegk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2qmqsbikx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2wlmolqsu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2ncwlkeug.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2vkpdksiw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gt2gjkvbuuv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2rootxhdi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gt2xcadvhcu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gt2jtyyekqu.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2shwkpqls.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bakyzjgu.html


<!-- 参考信息 -->