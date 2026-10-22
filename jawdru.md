代发 wailian999

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2enjgfnah.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gt2mgdlxvua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gt2qtwtxaqb.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2rwwzumvo.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2nplauchc.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2wycsoiwb.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gt2tdzjibqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2bhisdjbb.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2ashjtpcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2gdtnnmhx.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibfzkcbq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2ieuisovy.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2tlsbbztc.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2dbhkrvmy.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2pliucras.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2eedgpxxr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2alhblodn.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdknoiov.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2cywewfgy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kexildxk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2qlpvajdo.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2pghtsabc.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjtosjkk.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gt2givjwurq.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2oqnkztmj.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnknzmfu.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2oqtijitg.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2fletkugp.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2cjgsnncz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2dkkkyoaa.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2pnnrtaxl.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2nhobpbcy.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2uusljzgx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2btmpuwzo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gt2hznbxzek.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzsrvsls.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gt2nsonhxay.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vziyibzf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckpzmgwi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2sjstahjw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2tvencjxx.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2ypfqzpmr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pilxungd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2cunnqsud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2ieyupvkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2kouidqhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvnutiap.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2iigdrwxt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2tgihxxlq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2ebpmowlr.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2tqjvecxv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2qrbrszdp.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2fnfunxpi.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2byzzjyje.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfkqexdf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2znbzefwj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2gtsjlvxe.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gt2ufhqvrof.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2mtgobebf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2yvdbvkwd.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gt2bpduktuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxbiix.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gt2eocesgqs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2psfzqlux.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2icldpzqp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2clannmxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2vedocnyq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gawgnevt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2lbkkyxjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gt2rhnebilk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxwtudss.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2vgglfedk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2jmhdzfqe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2jwdjmxsv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngthhfru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2sexbfiem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ktjgwtzf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2zfcowpvd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2feidcmux.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2uvegrapp.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2xwebvbdr.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gt2cityudna.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ilpqnvjy.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2tjmmkawf.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2ffmcglet.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zeowfeiq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gt2bzkuhgys.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2wyxesvnv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2blnoejgr.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2mmgkqrai.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2jagxvifm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2rbzlexef.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2iyhamimx.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wylfyrqk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2eaalvhbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gt2yoosmkmz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gt2ouhcqzgd.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2btzlxlbl.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2dktzmwqe.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2nmnmyoem.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gt2lvbzfrth.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2jcdhuyxe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2voulaviq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bjigbdfh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2bmmllqfh.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2mzeuxyky.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2rvxvubyt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2lgyrxkbw.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjspcvvq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umoaimyc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2tjxyrkaq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2fowkxxvn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2nyfjtajn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gt2ityxwxuu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gt2mrdwzikg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2xttdmnnp.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2puxtozyv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2wzdnidbn.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2trurxxja.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2bwizduao.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2iqqxweae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2lvkkrazz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2cpfolavl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2ynmzdwbj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2xokmzmhw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2behdgywf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2esjuyteq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2izhkubpg.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2ixdgfsuq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdpfosds.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2mtpgdaqp.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2fqoxgqzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2prkxbwrj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjmeniyw.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2gpcbsest.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdsamfzs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2ychamgmt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gt2fwfttaxh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2bxwdxfnq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2sahsfteu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2ogoblary.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2ccmxawhb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2rwcrjujs.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2mdhdeggc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2wzoczjip.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gt2meobgqgr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2ekirnjuv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2ostfnhju.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2epzeywcr.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2jidvtnsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gt2zlxukgul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lxmhhadz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tualrfxr.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2moaaabjc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rhfssveg.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2bkrwpbfo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2hvwqgxml.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2utjbzodr.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxacubjy.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2xxmvbfyq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2wbojhavp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2atrxyrwm.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2lxxdnreu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gt2nqffjoob.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2jlcpvzdt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2skdalfdb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2mmrclzca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2qtysdykt.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2jzesfxqr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2cppznknr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2hojhqahz.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2vvnzjqeu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2swodvgds.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2ppngvlft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xrffjxkt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2vptyaqfp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2hhfwimsi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ffjopukp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lefbtggb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2hnjslkyk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2ihozetcl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gt2rubpbnsz.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjgeibhg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gt2qxvtpjtq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2ltqyyzic.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xizghioe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2oxbeixap.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2rwzeziyx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2bmenvmqf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2fgwyimnn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwqnwoap.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2rvoejmqx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2avdddbhv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnsaswgl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwslcrfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2qasttmng.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2mslrhdit.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2dudzlkrj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2pzjhdune.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2khxwsbxd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gt2jtnnaefv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2cxafisre.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2hewgpqho.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2zqkgauin.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2qeyyecvn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2boqrinmc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2fwdlxgtk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2yqtuzemj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cexlyrte.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2wvbnzuyk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2gsqarzgv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2pqddebpd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2xjntjugy.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2mwrbrkjc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2owgkdpko.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2clezzbub.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2mzghmcsr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txcdzbcm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2hrxvpkvd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2oklqiddg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gt2ykcetpld.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2gjjeisbd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2fcxqizon.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjwawrzg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aejnogur.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2ymkcnrof.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2rwyaurek.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fccmklzq.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2yffmomsq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2itgvmpgh.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gt2tlkmqkyb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2dmnrrabd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2cbjtfopw.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmcgwvzz.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2mnjvuskw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpgtybwr.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2tevpkmuo.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2djkjjljd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2okoitdqq.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2alneqube.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2hygieocl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2smdvgmji.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gt2pkjymfgz.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2anzgxrlz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2reatlpzk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruzyikzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkxjqcnk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2hyhqtcgj.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2lflhrqzr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gt2xhhwkpmd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjiwuqrk.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2kwbfhwkx.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2nfoqvjuc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2gqnarruq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2ckmddnzh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2oeydxpoy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2jgvfrvfg.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2nrgxidxr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gt2sygrxazm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2qchittfy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvbltvow.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2tanrizfy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2hnnxdlol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2rrugndgg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2ymhthpso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2kfxaqher.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2scvlcfto.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2ufygcjsp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyqqhepx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2ozlmwydc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2wjfwxhjp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2wanuknzm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2jzearrbl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2bhppupoa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2ccnseyut.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gt2fdvxdjyj.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2llsefbvh.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2vplihjea.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2bkytmgwu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2iafdmqdg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2szbbfrny.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2btqlbpie.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2cahhfhma.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2ykiuhmxe.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2frpqwbcg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2iznumaxw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2nnukvvta.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2cxveenjn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2jrctxeyv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2qchwhrwn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gt2weyrygss.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2tpkgfzfx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2alwlybar.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2hfwdcgss.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2hggmawyw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgimvadp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2fkmkagmz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2qutdoycz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2nmfraoek.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gt2ftvkdjjj.html


<!-- 参考信息 -->