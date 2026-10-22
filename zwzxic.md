代发 wailian999

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2zjbphtoa.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gt2wobyuesr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcueipha.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irdalmnj.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gt2jbxxgize.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2rxgrcpev.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2ehaantfd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lotwocfs.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2yagxmvus.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2sdncpyts.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2dbkfupkr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2fsmhjppw.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gt2olfmhmoo.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2yssoqwsd.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2twbjogee.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2axgbulke.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2mqluazxe.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzvinlec.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2tjcqbjxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2guxigshc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2axgvvvra.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2thnadudy.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2sqzwejri.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2upnahtsk.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2ecqvhoib.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2eviyagkj.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2audguodi.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2ahpwixrw.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2wqgdrqcg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccapbpvy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2bldmtkte.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2vbhrtnzy.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2egrhpuzv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gt2cgadvcko.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gt2zkahjykc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gt2hraogqtz.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2rzilerif.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfkpfsmq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gt2inrffpnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2oxsdnkys.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qceszzka.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gt2lypzctgi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2rpytmkws.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbyxltyh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2emklaoja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2ccacyxrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2gaztdcbi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2vyqcdcri.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecckywjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2ambmzjhs.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2zrinrozq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdysictz.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2xfpqrfsc.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2bgdlnyvw.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2ateyxweo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gt2lncxilio.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2naqyklsd.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2jdblmmvu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2krmhxlmr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wjhbjmsg.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2myvmmccx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gkragkmk.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2owewqvep.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2tkfaxklq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2ecrtcvdn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2ulsacpwy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2cnpblxjb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2oqfbcxgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gt2qslkrnqx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gt2hbcsttiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2alymxcnr.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2wbrthjfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2ajybnoyk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2pwbnicnv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfvskzob.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cvhqycfs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2yzctlmpo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbbgmkzy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmbxujvd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2invhkhfd.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrdqljfh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2noekrfta.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ldkqjyyh.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2sedtybgm.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2hewskcdv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2zlzpbduv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2coyzzieg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2hmuyoyea.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2uqosqmsw.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksjqncne.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2ydwofwxz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2flbzffdr.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2txficfuv.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2yvmmqtyv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2aiazshac.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gt2bkzkkgws.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eamhupbv.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gt2ylfenoxu.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gt2bpoivgko.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gt2aulsrkts.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsuezjto.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2zxzaqltw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2fdfpirpo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2amtcbicd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2fzrjmyee.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2wovfsvbg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyazvszp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2ujirveem.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2egyukudm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2gzvpxjkt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvriqcuz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2vrxnvpdy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gt2npjrmsgu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2lqhyufrv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gt2gzaszeft.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2jhyrqghl.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2hjcwawuq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmuplinv.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2jdsaxzbb.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2evrzeqvd.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2oscbnejf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2ewybytnh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2cazulicn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2mxfobugd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2phcccxgj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2kgzvvcxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gt2rnemkheh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gt2dftycuqd.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2lqehqqor.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2jyewfobu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2lnvyrfll.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2efqqghwc.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2mlpgqtrz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtnpbez.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2reyvomil.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlcvhdcj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebtvwiib.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2byajeyje.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2lmxozhll.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2vnljzrre.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2zlxyzkak.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2jzzrfhwf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2rajgpxmw.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2mxmirldz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2ybrugbac.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gt2rlslirus.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2cwqfltmn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2cleuekpc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2fngnrkgf.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fosolcyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gt2voqdvkvs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2dqqqldmy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2aszcoagq.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2xejlupos.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vjwuooag.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2rcsyfbww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2mlftydfu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2nnvtyhii.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2cpfrqgdg.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2btzkexyf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gt2onwxnpmq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2snpcgamd.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2jphpfxgc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2vtwqrnbp.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2awnkagis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2axmwxrax.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2ktoikpxp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2dzqrwmtu.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2ypnlbyfv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yonctcuy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2pvaopvmy.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2nskvauck.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2qwuhtrra.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gt2ygvfzien.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2apeqmatk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2jnytsxql.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2zmlncvlx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2ajxwlbls.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzlqwveu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2qatjcoia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2zxsiszcp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gt2xjvqhqqh.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gt2kirfdftb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2zgnsqrnj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gt2fdqseagv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2tnxhgvlr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2clpmanxh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2jkvjukjo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2zflyvzmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvmhyzzz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2ioponunr.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2bycqrjnq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2jrwfnsez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2tcfondou.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2damoerue.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipjnodjl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2rdjuchfw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2ydbmakli.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2llmsxqti.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2wabqyhkw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrasyfj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2txlskgca.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2eauwamtl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2lfwvgxog.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2nmxikchc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2ubxspzxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2ifmxeanj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yckhefud.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2gtesnzma.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gt2znymyrov.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2dmgdjieu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2lxazbiwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2nqjhfctc.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbtlfxjq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2oaahxxie.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gt2fvykzjmt.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2drtelnqb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqzaanso.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2pspccenk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2jobprgbq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2zcpnyquk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2xlvripqh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2bhadhdua.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2gehnumzz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gt2udtjmcrs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2adrjlxlu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2dyxunqvf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2couesvgz.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2pryeflhd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2smxbgwvn.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2qzzcgook.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gt2dgvypscg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2ssyzpoae.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2csnaphei.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2kvnqhjui.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2gdyaragt.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2qijumhyh.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2exsfkkwj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2ooqyenek.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2kftlaqjb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2bhkbrgts.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2lprfeirp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2fqtohcov.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2mdneoecq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2qulleffs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2buqrbhjh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifoganqr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2xfuttlpc.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gt2jijpwoxj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2yvropuuk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyxigifi.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2rkvupjlq.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2fseilupw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2ggpijvfa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ypchdqth.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coazkmyg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2bhlornmt.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onmqnfsd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2evzezbrl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2edmeezjd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2zwcvgasp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2triqyvpj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2paxnftrj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2lpqfsszd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2xfwriigf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2oeoytjda.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2sgekkgur.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2hboprwpi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gt2arugbrym.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2jexnfcrg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2oqlkiwqz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2qlbvxywj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mctcdgnf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2kzuooebg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2maudeudf.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2xiwgjlat.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kiklorgh.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2ngnzgdqn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2ypehlwqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2fsrflboz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2jxtiwzqv.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2cixrossw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2zunipmem.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2ydxflpxi.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gt2abxqmuzq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2pyexyhhb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gt2fpasdrnb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2zoedbgla.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2wctctezo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2ujqejeod.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2gzfdwygj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcskvhgv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2fbmvrzui.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gt2krjymury.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2obnojfhn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2ldoprcsg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fticlhus.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gt2yxfkmini.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2ykchymfl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnqxhfon.html


<!-- 参考信息 -->