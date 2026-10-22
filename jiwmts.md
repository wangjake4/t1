代发 wailian999

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2ccerlbtn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqyrrzjk.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2ikacznqf.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2basufahn.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2pxrolyty.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2nfjqyygf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gt2hfhreyxc.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2cjwoxsvt.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylbjbful.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2vpajfvlg.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2xsoppfva.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2ehwxrsot.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2uwgautzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sxskfqut.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2vrmgnekc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deidngrp.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2zxnbdpol.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2tqhvtavt.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnmrppuv.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2gheqquse.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2rnrrrhyt.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aydunmqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2zcfrilzr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2njmwyood.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2oxssmako.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2kbjohlwa.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2roowpkol.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2mmcphtwh.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2defdxqnp.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2svzfoymu.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2raacxpux.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2vyuwnaeg.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2undggbwi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2qnrrwnhj.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2tkvztuax.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2lmhdmpef.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2yeqcufck.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gt2jrzbuhmn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2yrabgccw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gt2vakwdtta.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2bysorogz.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gt2dmfwgfpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2gwmbberc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2echlzuxv.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gt2qbqvzwtx.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2bvxmdtto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2tkrzvxke.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gt2kyuzwidf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2fomxnkfn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2pcnbvptc.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2btmmofdp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2jjgnvpgk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2jgeddaqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2ptmeyptq.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2xthqrezc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2gfqsnvxh.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2bqqltgis.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xusyhmuw.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2nudtvgkm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gt2hlpocusr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2hznydjuz.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2mbsmxovo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gt2jhirgrtw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hhextkiw.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2zauedngs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kmrjwkif.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2utseqqbx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kakuwgsm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2sqcmkdgx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvypopxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2fuqxxscq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gt2beesyvdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2ilgztasx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2pylgjjtj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2yojfzsha.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2wsjbfswj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2byrcljhf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2sgsacbry.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jdsecnsz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpxtktrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2nnzjoiyt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2kcuemsxp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2gdrbvstd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2fydurayk.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2gskduhtj.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2umlltmqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2omdgclxu.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2qbjkgxrp.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2tfwtdbvz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2zirgjfnp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2algevhnv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnsxkefq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2urouyqyx.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2gusnkfyp.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gt2wghmbdea.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2uqmgxwzf.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2ricozaxf.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2budxkcuf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2lolwudpp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2nlawhdmq.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwrpzare.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gt2phlkhypo.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2ctzqbfee.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2mmdtcpgc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2hoesgujc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojsiohik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fwzkftwa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yitbhtdg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gt2tgaksffq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2ehfxmbqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gt2bhirriag.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2ujtctbza.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2hklxyyda.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2iymvipgw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2najuazwo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2azrwigqx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrmisagh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2taovmboa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2bufjqviy.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2pytceosf.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gt2lzinmzvy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iziiofvg.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2uwwstvue.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2fivaomtf.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2ywlexcip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gt2edkfqtqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbiuhrsc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2prcdvijy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2jspbggtz.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2eywbgmjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2lsybctwp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2njfkgxsx.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2svtpvflh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2cyzkilid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gt2vhxndbyw.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2aptnolvg.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2hsyvktte.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2mvffjxzk.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2muxeqgis.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2quivzfbb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2jstazywb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gt2oxvarxcu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2mszcmbmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gt2glqhtzap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2zymdkueu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2fwrwjwnv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2qcvkyrbh.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2tpbbexgl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2cxnmdpjr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gklmsdlg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2eoynuhjg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2xzojcbde.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2lwxgnbms.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2igpdlwpb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2diragtxu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2iowyhpyy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lcwklnsc.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2oaqewahb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2akvkfugs.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2evpocqgq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2rheqpemm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2qoiczlja.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mrjwtemo.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2arbmkytl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gt2cerimlnb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2napbhdvh.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2zrpcztpq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2jhiueasj.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2unvbkxkn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2yowawtwa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qllywfci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gt2dynlpvnc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewskocnm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2doegpzdw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2lgsubenm.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2wllmnsby.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2suwafpun.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2mdepnmil.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2nysiqiin.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2tljrwnxc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpdlnurr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2edmtjsai.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2nyuxmhsh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkypufwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2hmnomkbe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gt2qdjwzzsd.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2ldtnyfti.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2uuxbyinz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2shoeuazn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2nxaglguj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2dzbsgvlk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2eahgrxtz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgosmdwv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdttivvb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2tbofeasc.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gt2fxbbehya.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2sdclrmaa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gt2rgkjyogf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2vxqietcw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2tzwqznoc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gt2olwnldbm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2ntueeszr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2methdmiy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2ectkujjv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2oxngdqwb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2fnfpzbqv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2pypnrbem.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2vijrnlyl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2lmdxogeq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2rxbbvtmx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gt2atyyiudc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2bsyttfvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbfyrohd.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2uklmvwlm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gt2eamiesui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2lgruloxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2wobtkkft.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2vpeittzt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2vrekfjdh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2gujmbogw.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2dcmncozp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2ticsxhol.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2ywasjwqm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2xacbuhdb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2hxzjmsib.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2wfnoxaps.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2gfqokpev.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2rrjwdhzu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2rpyrszkb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2dxzzgbxo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2fzpimnla.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ochgxmvg.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2cifybymx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wehvrkci.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2jdvecefo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2kzcsfkiq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2vgqrhnsk.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2mkyhuxzo.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2fklmrqgf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2qoczmlto.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2yziapbfn.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2tfybpddo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejcuqeho.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2glxkwscz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2nigpkkll.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2aydxcntp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2rmonvids.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2dfaobkbg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnrxgnyl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2dqkphrce.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2ddzhwbjx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2srmqbosq.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2tjplvgpn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2yxiegfab.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gt2raemyyrh.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdzosjuw.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2uhbtilli.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2bqexcove.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2qnxdwndh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2mvvijfrs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2mcuqnixh.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2mebtdfcn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2steufyyr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2btvqhdlz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2pxshcjqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2zrdkbjjr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2hwzljqmt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkmbaoiu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2aragstej.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqrqnijl.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gt2szizkttc.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkdqcfdc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2mynwybob.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2looitmjn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujigtbfw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2rvpurbog.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paakwgig.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2zrzaqkiq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2sgkkfcfw.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jguninuw.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2nupbjvoa.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2cycpkrrk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2osvldmie.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gt2tjvxymqq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2qddiwniw.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2kidhtxhl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2syrvmlvt.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gt2fdeiplkw.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2kuxavwvk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2mvzarnoi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2uwlgvmqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2cqxrropy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2scmrslgv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2rjeouksq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2gqogawbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2hrhstinx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2gaqummvd.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2njsjohro.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2qbhuzmvx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2bvlleroh.html


<!-- 参考信息 -->