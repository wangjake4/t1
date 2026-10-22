代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gt2zopwrgxi.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2qfdbmckt.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2maaubxme.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2tkoejrup.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eamvcccf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jimnziii.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2dlxqisci.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2yashegya.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2sgwfcmhw.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2rxtrdvke.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2ksejagrl.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2rifjynye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2skwxsebr.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ypkbpjvj.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2dbzmpznn.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvntjqyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2vrqoiojy.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2rejfkjxn.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2vfozytdk.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2txjskavw.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2fthbhckn.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2vearvyld.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2xxjhlnfs.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2hzastapy.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2syanchij.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gt2kuwxeczh.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2odbbzvwr.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2obyropik.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2ldfhavlz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgqpvvoq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2lauxebog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2kyznyidf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2sjxmhvog.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vgpxkfpd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2gdsnvtht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2mzmrmzut.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uapsuvyn.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2ewajteeh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rygrbocp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gt2jdlbcqsg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2fulglnma.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exejhcwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxnemsid.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2gogpztyl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzkdhjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2lnxitcjb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2mdellceb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2mwcvspys.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2uuvvacpx.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prpjochl.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fwlisifm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2zatvkntr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2gjnveexl.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzmjfnwz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2ekmuvlmg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2voxbrhsf.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2fgxqlnbq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kuywkgyf.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2bvxhixek.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2igekbxbr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2fmqesgis.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2bpnxwpfq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2lfdfefkb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2cwlbbjig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gt2pnfnvgxq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gt2hrgtwaoc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2bbqdlhdl.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2kcbgunhp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2xtxemnul.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2hoocdjoh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2cqvacoeh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2owjartev.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2scxhgjnp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2dhfhdbxw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2dsfmwqzj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2fpgplcwt.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2ijvgymit.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2rgvrltpz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2knjnooae.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkokcxcy.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2lrxwhszz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2xholettd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2kpnaizvg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2wpdtclqb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2mphesrhe.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2olocukzp.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gt2jxdferzs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2khjhrtxy.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2pwwemumn.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2eizmgxsw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2rlsbybxf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gt2tjeqgita.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2ylsrvcqb.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2akhzappm.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2monvdqdg.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2yjzoctoj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2saqlhjpi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2dubiscuq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2hmbgncvw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2eprojoea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmfdioyg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2ebgugyiv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2uzcmyttg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2togcntpv.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsveqjmm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2nuyjkogn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2xgnyxmsx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2sxgepvna.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlgjgjhh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2uqpqmaye.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2qsdikksl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2ymwpeane.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2hmdlwazf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gt2vqtrlewt.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2lxvbtcgy.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2reahmsmo.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ecbdfbko.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2zikifdcm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2zqgoejzv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gt2amgtgxgv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2mjibocgs.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gt2ienlgmtf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2udrpowvl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2zllqoicz.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2zcrlbpox.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gt2hrruqfpp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2dkhhgbqy.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2hlljjrkg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2ewyuatne.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2nvexkobh.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2vmcehyzq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2vjxgmqvh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzfcwspn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2lzbagfhy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvysbgsd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gt2uddytbbh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2aabwgqrw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2xwzksdjh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2vnqyyqga.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2apwgcgcc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gt2ynehwhsn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2qsjspskk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2vugjizlf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2tfjcjnna.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2ppijugld.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gt2pojkwofy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gt2ekfhdmvk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2yocrdifw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2onloyeea.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gt2xfumdmww.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2akjfvaee.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gt2hnsqvuld.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfbpgznr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2tmnadhal.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2cvmxoqck.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2lhakajqt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2gvjxnhce.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpkoxggg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbpxwxyw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2qflhijbf.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2qudrugwv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2dnzpxiel.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2pkjyoszd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2kvacfkkm.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2njhtjzjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2xibwxzkf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ttvqnjxn.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2akkomljp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2czrzrdqs.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2neiwdguh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2nzxewbfg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2uolbvfpn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2fkrhyvwp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynstfklk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2nvzmhpjh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2tkfmwgji.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2qjzewkph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gt2eiakpzva.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdbkrxtd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2swzfcfso.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2ebqaawjj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2ehdwjcsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvuqkqrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2tnedtxuu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2zzcfvgsm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2wlizcsyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2felyqjkt.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2jyhasxft.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdimabes.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2rmwxyckn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2fznmefst.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2pirqzbgo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2rtpwjbss.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2kwagqdhk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2qkrlppgg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2qzopjlrh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvwaunql.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2irflsgfh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gt2yrbnmypm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2dmpulmow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2eoxwdvuh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2felhffsp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2jfoemddi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2gggaxmdc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2foahyzoz.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2hzdkwmso.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2bdwtgwnq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2uqivhczf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwriqqdz.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2timjoccf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2zbpkmrmr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gt2addxhbnu.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gt2dufbjoal.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2qsmsfngc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2yuuonpxq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2efcjiqfl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2rvzhtpye.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2uwbjceqe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2iwmqmaux.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2celrwtbv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gt2btcfguah.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gt2yzklibkb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtrkkngs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2lafzwbic.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2xwvrqpct.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2luemudap.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2mtlgpowc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2fyozynuv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2aovijzrs.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2yrycxivg.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2vbwmmpxu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yumxznsb.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gt2cbwqtyyp.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmndyykg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlrnqlcf.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2kbxcteft.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2cjsyxkrx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2qzbvmiri.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2gvulgzja.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2tzskkrna.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gt2ewzhhoqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txdbnxpf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2iqivohhv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2qmahhemk.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsljvmup.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2qpyxbsvl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddlhvecv.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2cpftqxhg.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2okerormf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2bqvvrbrs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2mummwlit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2ilmruijm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2ctxwkqsv.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gt2fzwtaksl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jeoyrdux.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gt2cadhvsnc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2ampthpax.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2gkxbfuho.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2zibhnpje.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2zdvoobhi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2bbimqulh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2hlhmdzpk.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2awsukxqu.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2qqymbgda.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2gwztukhx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2xhmlfgmo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2azahwifw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2gngekdfl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2ebuysazc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2unbclyux.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2linnkhnh.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2uzlijdkn.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2hwjeypmr.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2yzybeazo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2qumlgncp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2mtxwywsf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2pszdrped.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gt2mpfiwakn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2pxpcvhck.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2ygvuftat.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gt2qlgedibz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2mbdxynqo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2ggjlctks.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2pgahtkln.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2kwupxfoy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2gpkcxfsx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmepvskh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2nlgwzxps.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2oairbeep.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gt2iiroftca.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2psdcdhsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2nesxywjs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2wujzzmoc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2yjxtcepo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2milmgjjm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2fjrdwxsz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybieahwz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gt2gyldachp.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2kwbtcazz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2kuxvjwxn.html


<!-- 参考信息 -->