代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2shfpoesm.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uztcsmrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2izkoymht.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jsrsmnsa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2oqiwjytw.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2yxzsmcbp.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2rrulvnsc.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svmmjzta.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2ueujvhke.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2pexeblob.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2xnnioohk.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhgodvmu.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2rysnpyau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2xegyuaqe.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2idicfacn.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gt2oloqcuhd.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2yaxopdhr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2ombbrqsk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2fomyabbx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2cnxiuxre.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2kanajggm.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gt2svavmziq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2qlpwqqaa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2nbmebgpq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gt2vzrrnzoh.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2ewrxndab.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2nisdqude.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2bjybrpem.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2fiialljr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2jkemuhfn.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2kbryjddl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2cvlzogtu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2nprpexzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2htpkvykw.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2hhmfvbut.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gt2nqtjffqe.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzynjrtj.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2pddyauwj.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yrdyllfc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypwbuvmu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2iihspkcg.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2jnlwgfnq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2wxkljhho.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ccihyjus.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2oeivqljh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vywdramv.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2pmxgjzfc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2yllfzrfh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2aairwlvq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wphehmfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2nkipcivh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2lofbhoqs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2wnfcmrch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gt2mdtfqtit.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2gqewqnwj.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2pjugbxvu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2meyxobwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2nekjyoht.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2emwopjwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2dyeuvllx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xwggdaix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2hfqlkaom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2fvxlywar.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2lprjsqfi.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2rdubcubd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2qchdsmca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajtoorqm.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ennvieex.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hicbvgyu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2dgkhrutj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2evoezoff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2rqvaixbv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrihxnfp.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2rbuiwtdw.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvixtqzk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jgvsnqxq.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2mrhceopn.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2zkgnkrgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2qxgjcqmj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2imrekgll.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gt2iyhwegqj.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzzphjbx.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gt2iaoiwksz.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2ygkckjwd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2ytuqcdde.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ouadnkkb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2nmeftisc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gt2vifyrniv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2aowbjuaa.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2rqynbbyc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2szcazzhj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gt2fwjqiofl.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2vjsbbans.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2vvmbfcga.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2gzdigsby.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2macjfvin.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gt2ypecfafs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2abqorffm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gt2jlwhrjkk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbnqofrt.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gt2ibtbdlmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2hvajnbqy.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2qwlipsnj.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ueggmqtd.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2kgaoudid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2vzefmjnk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2rdlrhzjs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gt2zuwprqmk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bnxciosq.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2angctkde.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2zcqodttc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2dffpnkld.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gt2uncnvkrs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2mrcwnqri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vofjbius.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2wgmwcecb.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2aoldhgmx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gt2rnnmyjyt.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2mcurnbig.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2tcpkcddg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2aoahngzc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gt2egrirqct.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzdveeol.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wevnuemm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2opewfcrv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gt2einvsoub.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2woyzukit.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2baojjuwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gt2gknuxmtj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwqxovdp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2xrabvyrh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2jiznsicc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2xrayzitj.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2qexpvsga.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2pdedmkki.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2ijyajapw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xaxtrspd.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2ylczivop.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lzaozgzu.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2uulpijqj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkmkqdcd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2abjwqsgu.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2mqsvgwpo.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2nbtcluwk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2lamrasoh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2tnvzlvdi.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2timrksqi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2vuxegnzu.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2lmcnrusp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2aghsypvl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2ibadkkod.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stlkrgeb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2zhupgwtk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2zqptppsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2tsaxaron.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2wrfwpsjz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2afiovaqa.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2ldgzxnxp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gt2pvuutklr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2jshqtazq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2jtxmtjso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2fuqbcivv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2gxnjljvk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2knhqvigr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gt2mctjwvon.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2dadvthgd.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2htbghxas.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2gggdfvaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2hiscpxhq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2ghvkzfif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2lzztckxk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2fefhzykt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2usrrfvng.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2hnjimtjc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2faotfuqk.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gt2ucsssvga.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2odmsnpis.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2vgfbszur.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2rljykthu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2dydpyibr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dslwqazp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2uxfdjhcu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2eyhuhodt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2uuyavzbx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2auybvjgz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2qokvdgkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2eyqebvrv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sugcyjna.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2txgnaexg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2numdwwlw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2nqiupxfs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2plgvvjiq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2smatbknz.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2gnoppohc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdilkekj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2iudrrwvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2usquscmz.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gt2kwzlgfds.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2alkqpcaq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gt2rcqlqglf.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2njhcczdd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eiqcccmq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2zaxidmee.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2lyaicjva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2kvwecjoj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2fbjwqhcg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bylxmoik.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqdnqdom.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2ycvuulfy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2hokkbdjv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2trzetayi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2isbwjmmv.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2hhcwwdku.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2njghdxaq.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icsejlzd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2znqkesmi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2kyvwhues.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2wjjulujs.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwsmllsk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gt2vdzthfaq.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2osypyvwk.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2aqyqlbmp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2ghufbmoc.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2evcutyps.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfamynzx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtvlmlns.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2hhascnmf.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2exvclzzs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gt2kcwfsmdf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gt2idcyuxje.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2ngtgofsl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2ikkpscug.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2nhqwhylq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2vsahdilm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bidqcvgh.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2axkhqomr.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2hbieshkn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2vprryned.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukisrcoe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkpmgvsa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2qkseixtt.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mehpcgdi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2ftisaamg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2omqqosdg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2tdewxrkj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gt2fteewwlk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2ispyfnby.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2umjywmgr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2maiuozun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2yadjknkp.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2cktnobrf.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gt2kdsrmkzv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojqmllru.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2auabajop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2kwliprkh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gt2mdxlfxag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2srsixlvr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2zizpqinw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2bgorqqqe.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2neochdjd.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2akeeoijn.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2jasflwnn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2ovsgyiih.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2iqaegewj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2duxqurgx.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gt2lbglhnrc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2iiednjio.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2qxmigrhs.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2svirivuh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtwtydfj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubjycqdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykowdyte.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2ohxlldrp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gt2ftlfoxik.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2hlzrejrd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2jsuahubm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxsofukl.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2sydqjljj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eroafueh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gt2ibthvilf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfsdcjgt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2ywylbsir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqnolsac.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2kbltvcqy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2qigduaby.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2yaajpzot.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gt2iduxhodn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2zwpeeidz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2wesdrnju.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2rpekybjs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2qwvbzhdf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2fjkxglck.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2uewaihwq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoaoqdvw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2jigacmuw.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2admxvfes.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2jnopazwv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gt2lshxapam.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2czgptxnq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2mbllgtlu.html


<!-- 参考信息 -->