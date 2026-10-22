代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2hwxjyqpw.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2nabdqsaz.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2ygpspann.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2fhnctyim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqdxipds.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2sgwyccpt.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2crsgqklj.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ogeipbdl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2nffizhew.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2dwtlcxvw.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2gcjteexe.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gt2hzvzxgpc.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gt2wsrjpumu.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2hkozavyz.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2khhslghs.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2mxifxigb.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2nxpsxlok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2serjyqtk.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2bnsjdtrx.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbzxkutk.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkpxtqvn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2rddpkpqe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2ukmagxsv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gt2uavkmjdt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqzxalbo.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qvlofclu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gt2yrtzubcu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2xfyztinx.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gt2lqfacfdq.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2uxqfywux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gt2vlqznxqh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2zbejwhgg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2yyqbkxcl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2krugrdlw.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2fqtugjgn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2tlafkqdo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gt2iuaqndyr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2udrywgwf.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2acgleyjq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2wccxsdkd.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2wzzejlrs.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2msxnybyc.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2joobsuae.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2kxsyffyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2ckqhaijj.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gt2awnuhfvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2ozlegmqw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gipxnkup.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2xronivxx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2cgaxapfw.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2wjafljuh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2arxlggam.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gt2xrwazqkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qzdrngqe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2xgclqkqy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2uygkdlng.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phofbzym.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2gnwzppif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2eukquazn.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2hufnyhxj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2abenitdy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2dttmcyal.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrajraww.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2plghhoxm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2fazeygzy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gt2zesajhbi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nnflqlnr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipojcecp.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2pcwywfkk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gt2gdcccfqh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2qbggqbhj.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nehooyvb.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2cmqocsmo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2bflxyvvs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whtcgdwn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gt2zhxrqxyb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2btmhvhzp.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2wzcuskcs.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2vxkhegxz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2cmtqqahm.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rrswjiqo.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2ulvfhhku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2jolixzlx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2otldtdca.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2cblsldue.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xermuzao.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2idejqsnj.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2qsceltnp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2wxtwunlb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2vdlbznsc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2vtyxhzdo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avrlxrka.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2lhwmiwgh.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gt2nlnkzozc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mmyojfxr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2aowqdeve.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2hnsqbjsg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2rpmnrbgw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngxkhayg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2hpzytdlt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gt2hlaclype.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2zvcudeml.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2djjfqyqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2crnwemux.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2drladlkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gt2jfngxpyk.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2vdltyovy.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2doikadrd.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2fjlofzqp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gt2wkostjxz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2klcaxvhj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2xkvoehcr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2awvejbva.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2egkviyfw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2blqhipwr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zymhqtwd.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2pfshzjcb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2xslfrhbx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2cqumjjbw.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2ppyghjrh.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2rtwsmhlb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdcvwmzq.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2zopvvojl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqoylsry.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2dinhzeky.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2nejdpbvp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2fmehsxmc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2ieectwps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnjjnytx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2zdpjlhmn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2vsyosdwr.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2yyvwwhsu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvjjshpp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2nnjzbzow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2qwayfqjh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2rtcmtast.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2iftgpang.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2cvacuvuo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2hqgbtfuc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2lrlcwwyl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2nigqqaos.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2epddkigq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jqhkcacy.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gt2vdfetmjp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2mredzdkd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2gntxfxhn.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewlymabd.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2mibulzcm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2bppapxgs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2dzqboxrl.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2fcvwojso.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mayalxks.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gt2bxbezgux.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2zkceqvca.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2cxutglxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gt2vazafywn.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2wxhbzade.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xijrzmbj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mqtzohqm.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2junrzjqo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2sksxhwlh.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2tzxmqbtn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2bexkqvlg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yffqzfyl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqaetiql.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2bdwfjjgb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2efhxydba.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2qttzbmia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2drixoutu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2zgaidscw.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2cbewuoqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2ihkrxqbb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2cubmomae.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssbowuhe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2gbwyxtyc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2vvtpgyuu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rszhjjbg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gt2xqlhdxtv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2gqcsvbji.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2stnnxsme.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upwvvxnw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2vjjmikvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2tjdotvne.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2pclexyaz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2rirgstie.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2tspbxecj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2giaeynhl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2yglummdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2uotxvvnp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2ogsstisg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2exfmcyvw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjglfygb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2lduixuxm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrxmcraq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2xbtmhnpp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2aygyfacc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2fncqyoku.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2mvyhcebr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2teevftmo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2baclddqd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2mcjesead.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2faedwpyp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxhlavku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2porswqcb.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2tsvxcqny.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gt2unbtrfuc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2ebedveyo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2ydliidid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2bywxtxoj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2jiwysgyr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2hyuqkvxp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2mlepystm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2hbhxzynb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2wfbnbykx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2guhkeqcd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ykcokbik.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfjsbxaw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpgyzijd.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2mnthseqp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gt2vkxumbxm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2zxwlcoje.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blchgnmc.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2qwyapfvf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gt2kvtolbrf.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2jfjqeqot.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2ugkqafyl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2pkdgtfhp.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2vvtzjden.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2exdbwupm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2jgthndga.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2firezyvl.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gt2cvovwyfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2gowfzesg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2bryutbab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2nbvultum.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2bjjncgjb.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2jmmjhzhp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2gcvxlxko.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2pjumyaxs.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2sedfuuho.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2itxffppg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2cixiccmi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2hdfcivfq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2lmdumtnj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2muzsloau.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2cnkihjpf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2brksqiti.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqjvnglq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gt2vnjgxlvs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2tjklotyx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjxfqrxy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2hjdlzror.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2xypbsvdp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ekqwakto.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2anpardqw.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2gqbbgrbc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2hmyhuqrl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2xzmfkifd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckjvuilz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2bygfmsau.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgjfluwa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gt2fdsioake.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2dnkxivca.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2lpesubeo.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2xrexbqvg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2lqrthjqm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2ulqbwiex.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2synafzvf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjnmkqay.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gt2ikdmwztc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2fcnbnwwe.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrlsunjl.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2tayflwyk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2zybekcgo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2liabsaxf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2qofvmaug.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2hbwpcesh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2opmuotqn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwomyfgx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2ncswuuzx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsnbmve.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2wablywaf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2juzgxeze.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gt2sqhrxgkf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2fghcsaly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2rpgtdamt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2wonawneq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2tdzvmqcv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2zxcpignt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2tygnehfl.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2ltidtoks.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2sveanqop.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gt2domvokow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2zzjzwwfr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2aocydutw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gt2ujjgbggb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztmflfrq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqyghuc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2ivacypbi.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apvngmtr.html


<!-- 参考信息 -->