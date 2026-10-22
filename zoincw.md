代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gt2eoqqoqtq.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2dobdybmh.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2josbcrbd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2xphaaslg.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gxhsaaza.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2dueipiux.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2qrcwilod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozknzccn.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gt2smwwakdm.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2ykgziidc.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2fxiyjjzn.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2pasmgzzm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rewfyccy.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fthpvqpm.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2xqkogqkg.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2faxoqkqk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvfhkaym.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2okvoniyg.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2lklwtqrp.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2mjqwfxyu.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2dbnwyopx.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2umcigojn.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2rongjjag.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2mollfwap.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2qtknytgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gt2lvhuvsep.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2cxqkifcr.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2kjgevdke.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2ztdqhemh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfrmaajg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2qrrlsgrj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtxvwexm.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gt2ykfwbncu.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gt2ernxrbrh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2ojjqnhoi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2vcoqkrub.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2hudrrglx.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2rmhesnsu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlyvkdrp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2absljviw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymayndpw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2vruxldmt.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2eqeynumq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2rtirzhhw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2eoobprsh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2yshzkjzt.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcbxenca.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2ssefmdoa.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2ntldgnes.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2uhwsqkrw.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2cueolldy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gt2dhfkokxh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2udjwsgfl.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2atggikox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2wtetcchb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zdzmjxjt.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2qrdhbgwu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2slgwyzck.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzloknje.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcbfakxy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gt2rgycchiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2iczlvfxn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2mlnlhtso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2quqivbta.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2iaejkffw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2nvnsitox.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2zxlzpjan.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2qdjufudi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gt2ffcgfzbu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2byxmamuo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2gutyrurv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ijfqcjez.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jnyaekpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2hithtyko.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2nibnxmhi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2vcjvvuvh.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2uirtprvc.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2fjmceakv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2pjnqbyyx.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2yqmatpid.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2gbecherg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2pstadthc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2rvqxickf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2jzyecvgb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2xbpxoolw.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gt2qiwnwqhh.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gt2hswueadp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2jrmppjgt.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2bitilyyc.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2phovelbl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2nmtqgxpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gt2mpnwxact.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gt2urvtfewj.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gt2blrfmwkv.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2enspyfyb.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2wyeohatn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2bsatgbtg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2dgdeqzim.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2zksrwjhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knllunwa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2njyctmio.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2ryrlfkoa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ldgaxtfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gt2nctarqyw.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gt2ctklyand.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2nnctjuyt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2avrstyhh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2xxecgguu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2eggunzel.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2soxrrojd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbvtqqbb.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2vapmbwom.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2xgvlkgif.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gt2alfmhmwq.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2qnvcoqmk.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2pnxyrmou.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2ojxwmxgj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2wanthaey.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gt2otcgwlvd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2rfjvwquj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2agrjfmne.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nznxltlt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yblwtfvj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2neacnhre.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2tglzglgp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gt2zlkpmtmg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2mlqwhvhm.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gt2lllascoh.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2pkeajnax.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2tlckejrr.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gt2lnxkimys.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2zlpbsnal.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2mtqqzmjw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2dcabrnxb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2ljsclgsv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2favkyyju.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gt2vtcklhhs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2sedarysp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2rvdpwxsn.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2hjnqcvxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gt2msnvqukh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2wmxiifsx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2zzxjqtyd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2yezjuolu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gt2ggobpmlp.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2fvrhgvgf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfxkaqpc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2rpmmysbr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hrpizbfi.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2qqxvuqcl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2haivtgkl.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcejsem.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2droociyi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2zhmxpuek.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2egjsvqjs.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2fabjnbsm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzlfdmzg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2uoaxqucq.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2supvfetp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2gsuuleoj.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwldwiuf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2lcxakjlz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2nnlvpxie.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2sxrigifk.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2hulvedww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2hwcnfvaf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2mgbpgwzp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewedeblk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gt2jsplmbow.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2owzukviv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2uuohzjwa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2knxaythq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2mulwbenf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2qhkveosz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2bcdhfebm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2kyhzlenr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gt2hyvvarsp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2aymcgmdc.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2tymkpspr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2xyujgmgb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2jqsigdmq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2exdzwfbw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2fddxldnn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2ptxkvhfe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2xflzwmbz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2xizdobmn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2dpjqzurz.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2kylinigw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2lotwzklb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2lczjuiay.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpjejeul.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2bsghpged.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oznpqtbq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2lopiudgh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2xcglegls.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2hxiyvtpv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2hvmnmnzh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2arkshgyg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2oxnsnjzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2uucxbhqn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2diawwlof.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2wlhangva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2dfzznwfb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2iiisjyeb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2iqqqvleh.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2uzffwjuh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2fumouzbl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2lftnyjoi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gt2kivsevdm.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2tgfdzcaf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2konyjfjv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2qsitxmvl.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2fhgmlpbx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2ycniihms.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2ecavkepy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gt2cappmdyn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2qvpbehbg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2pftnbpbz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2cbbbisfg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2dfiytxxr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrazhegu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2xylsjxzy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2ofgijjnu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dvgyayej.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2ifqnycsm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hantixgq.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gt2qlfqkpfn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2idmddzaz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2kcyqxgcf.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2agbqvxfx.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2wzurlijk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2dporydwy.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gt2gntwlsid.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2ijoihjmi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2qctayqut.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2ogabucxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2svtnifjo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2fcfhsgzx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2qypadgao.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2vmmfwhdj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2gjpcdlmd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2uflyzptt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfwkghbn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2ohcqwwey.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2hcfnblkz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2nnkzbjgj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2flipuzev.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2wehrtyry.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2qyrplmmm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2lvcvwzpi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2rqdrfxkn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2trobbnom.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijquwcso.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2vscteihy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2dbzsdhff.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2cehbadkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2cbldpxds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2urjxlxvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2bjlcnmsg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2eakgzrne.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2cpgbdqpp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2mxlxnjvm.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvtnjjvf.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2kjzkjksz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2ppvtqmsv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2jypmrgqz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2boqtuizk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2qiosltqg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gt2iuqrccee.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2fpfssuss.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2zuuxbfwn.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qggqjlnl.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2ecciysqx.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2zswdusvu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2kwmeawkq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2ndseosln.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2yhczcrmi.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2tzaqkhyp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2vtlzwsuv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gt2oamsepyt.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gt2bsozdfdo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2ligoxiyi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gt2mepldjmi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxuburdl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2nyrsiecm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2ajsyllfa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2mrcgelyv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2pclamicv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2nunobpfm.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2znmyunsw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2xodofqji.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2tpfslbzd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2ynqcowry.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2euwrvmvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2efvrmrje.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2uauvtrgw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2gypgtvue.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2yiwxagxs.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gt2hsjptfsx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2idvyixkr.html


<!-- 参考信息 -->