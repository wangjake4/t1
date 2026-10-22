代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2wmvsxywj.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2yzqsucsp.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gt2vsbewzhe.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2fkysfrbp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2zpccflgv.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2qsqswejx.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2hajfrgbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2rkxhkzsx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2togynkia.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2moutznzh.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2ivanoytf.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2wxdnhjtm.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2smxbgrek.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2xlxtlpkn.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsrtiakf.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2sqbccrkg.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2fxhazust.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2vyjgneig.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2yqhczhha.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gt2exymdjxt.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gt2sibzthqv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2sozgelhi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtjzpbqi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2fhezhzna.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2blwthrmu.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcdiayle.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2ylnnnlib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2btfwtqov.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2wbinaoxu.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfgppvcl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2tfaiqxyk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2uonxggiy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2rzgljojf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2zuxjgfas.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2tcqlvwgy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2tbjphujw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gt2kjeosokh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2olghmrrs.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfgmfbvw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2awzmkqeg.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2oroudhxp.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tnfgmnxd.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxyhptuy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2wcctwzln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipptzyrv.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2bihbfdlr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2eujmdjft.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2msogqqhz.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2xybtvgap.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ymgjvxny.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flfybxxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2ajgzsqak.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2lpdezimv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2dxactzul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jluewjqu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gt2fewpqgsz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2spiksmpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jmaxwafy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2ubvgkbqz.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2qyealsei.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gt2xextglpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2vwuxgrpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2opakndrf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2bfoqsfhw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2onscdldx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2dodxemis.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siddbaxx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnbtcvwx.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2vrzsegyb.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2ebjefira.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ryntsebj.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2hkdmixyh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2lqrlooyr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2itacyqch.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2fkwwmcqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dveffgeu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2egjrucaw.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2ziwzsqox.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gt2nigeikgv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2skghxeos.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2uzqrklna.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2qimmazat.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wkgydajq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2skyaurdp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2vbabykag.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utivipzd.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2otpaulvh.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2wualsjzt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2vcfabjaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2kwydvkgu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2geasapbt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2lqctuyir.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2qbfwdsdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2wpfyayyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmpxxdlq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2rgzigoca.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdqxgxek.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2ejbacjsu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2qsdydanq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nepmlxms.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2gowdwhkf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2vwbhkfnw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gt2xehyisvm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gt2osbmxjqp.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2nfsslvkj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2wlzbenrf.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ksvicyrx.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2jxbztrhj.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2doqpynqf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2shzydtea.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gt2blpabvzl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gt2hpypcjbe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2grhfxwmj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2krjppvvc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2gpgdgqcm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2pdeuaupn.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2jxxqydeu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2ulgvuacr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2iohrygty.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2eebjetkl.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2fevqearo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gt2whtenath.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gt2igddoncz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gt2rlmcyxdy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miuaawmt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2iviqzols.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2mrcbglfx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbrpsukx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gt2ttlaiyvy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2shijslfv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxpseas.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2awnskxjr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2ycsforkz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gt2anvfsddd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2tbrkfary.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoufnpzr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2pnnjscqc.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2xpleyrub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2zraxdseu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2ktuiyyvs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2anxpxmie.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2apwesjsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsfqnsa.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gt2fxpqjypk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2rvirbysz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2etrlfxes.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ghmcarqu.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2ehodoidb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2hfjfajtq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2dmagffcb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2weaaoxbd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2bctfsdjq.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiuuowmm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2drizhlyb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2kycufakg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2qvryfdvq.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2tzpfaslf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjhejval.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2yefuifph.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2tjlulnyv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2zqtmoqdn.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ogvuycvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2brpupijh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2mjtmzsie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2lgwrvimd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2uuapxhqx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2krhuwdod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gt2dctyehsi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gt2lbiqrnxz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2zjffblsi.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2luotefqt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gt2ntqotzru.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ummgwlkr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2zaqzozno.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2bupswjxf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2efoawfpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2pihipkbp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gt2lgbwzpzr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2lfosvivg.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gt2jarofzgk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2ntufkecw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2aisiroid.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2kiiybrix.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjcnrjns.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gt2fgmpsgqw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ehwrxdko.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2kewrufya.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2mlboaywk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2zmbeqwka.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2rprmqfdb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnlkejdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2ygrqlozw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2qxdbprpk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2oklzgjxo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2ktbtwekk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2etuhnyru.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2niksezup.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gt2cndzabho.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2ukyidkpg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2riloukvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gt2sserdwbs.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kslljzon.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2rbmnoeqf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2mydouvus.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2xztdrvld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiqgrjzs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2kutnmudl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2nmvomjkc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2phbenzks.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2slygidxp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2fhyzzgdq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2kylazkfk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2onocrkxu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gt2jslaiqtt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2pslrpiuj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zyeeyphb.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2ystguftv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mizhcwqz.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2dhrdjdqo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2dgezsvrg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2amyeilvg.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2iatxcuqy.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2grtuutzu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2rhgjdarx.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2qkoehsyu.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2fbzhfjuk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2imjuuuib.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2gibwuxmt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2izlndtjx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2wmkhtyjc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gt2rswgykkt.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2qxzokbpx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2uquhsgut.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2yhcmtrrv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2jlujtfuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2gttqrpvh.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gt2gjomjjsd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2rthmgjba.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqbsstgx.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqxnvgsj.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2orcwnvwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2hvqylvhh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ssaubonb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2jytaavex.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gt2wjviausx.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2zqofehmc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2ohhejoee.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gt2pyfebden.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2vcqcszym.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2xldymzso.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgjssyrk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogflrkuw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2kixvqhlr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2aomucroa.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2txflgfmn.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2clqmbnyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gt2frhzvogy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2uzasuysb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2zwkdbvxm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daoxhwvz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2gxszltnk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2nzzogzwu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2gxcuyvul.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gt2jpxdbdlb.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2yerctvwa.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllxclxn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2weqgoluj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gt2khhvnemp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2aunaizwo.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gt2gjrzhbgi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2xvvuflsp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2oxhajqew.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2iykbyeqb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttnnpxvm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzbulhds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2oizdjqkx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdegcvgo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ezmvigag.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lckhyzpb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2hasxudor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmczmlyf.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2jzdukesc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkxbblql.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2alqdoojs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gt2vatkrfxb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gt2kqpwwfsc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gt2toznompa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2jvxltfxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2janvgynm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gt2qjgmtvoz.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2nnrrkuwn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gt2uadbjnrp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2oopzjjsy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2kuuzlecz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hndqmviy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2dpvpwhag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2hqefwtep.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2hkgkjzso.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niijldtj.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2nbwreprx.html


<!-- 参考信息 -->