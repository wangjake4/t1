代发 wailian999

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2zjrvtovl.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2gzokwrkh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gt2xzvtekbm.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2lfgpilpt.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixvpbhpc.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2wuqboeev.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gt2kruzkfyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kezfieqx.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pgceqocx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2xzaakchl.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2wcjiiioa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2gonoalbq.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2ommrhgee.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wedlshsv.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2pzkzbohq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jukugjrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2vlznfzyl.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2cuqqglit.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2nvzipicc.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2grvllvmf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2yyzogvbp.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2hodskwhu.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sytpfjys.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2kuykuppz.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2yaguectr.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2fjnzzwul.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2bzofvjwx.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2iyjwpxuf.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2sqwpfiwv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2basniqhy.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2kfozhbyx.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtqkldzc.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2topjuoqz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tcodljou.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2ssocwykl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2cqahwqlm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2subpxran.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gt2mnqlqqjk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsdpckrp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2klhqbegp.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2cfbvymrh.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2fptlxvpu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2kcuyulsl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2pqmuxyef.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2hhziwxgy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2mmhlfrej.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2aonxgehx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2yfhqbrgv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2kdpspzsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2kzgtfmao.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2lchwlimt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2tdsbhgbj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjamrrdq.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2thmkanbr.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ryxtqgan.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2ikmerejk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gt2kisrqwvm.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2cxsyozxd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2jkhddyec.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rzwdxsdp.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2dqckvoew.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2klwqjduc.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2zrdbmxpp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2yvqidmbw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2vukwwlpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2yqsrwdwr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2gqgqijpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2yjjppwnl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxjscxls.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2ipwakith.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoftrzjw.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2bmcljgzl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2pzcjxnid.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2suntztmv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2clurkuhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2kpnutmew.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2goinyzlg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqbrdjgo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2wivwyciw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hwfrgpbv.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2couumvjn.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2fcihpfrc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2ltkposin.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrvcbijp.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2droqohnj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2wqyaybid.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2lafvefym.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2tfzwnoyj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bozaprta.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gt2bzyxhkpu.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2upagtkze.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gnwhrgpq.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ncqcycyp.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zjjgirtv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2lxtxdxft.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gt2qtbeyqfs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2dbelpydg.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2cclufkly.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2lkdyopvb.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdqyujmz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2bbsozitm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2obusqkge.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlbujyad.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2wgtkockt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2vgmxxnbh.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2oummzidb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gt2mbxunvum.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2ybnmpawv.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukjlmrun.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ftlknfxs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2qucndvwl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2meutfsfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2lyfybirp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2boxovgwn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gt2bkneqdgz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2rglpfpkq.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2jxzchump.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2xvmstuii.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gndcturd.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2qzqlochn.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2mkjrkksr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjwdmnck.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gt2lokuzpjo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2xunwzase.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2hhndepxg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gt2blzfzbkl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gt2hgaspfdp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gt2vqoglcjf.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2pfaglozl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2jxgdigtw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2flbpouux.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzrmbokq.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2qitzcdwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2zauqoevc.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gt2ycvgbfcf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2mpzddyqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gt2ooctwira.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2xnhaelfg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2owkdlysf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gt2gzvvjdjb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2mzupscpn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gt2llqjfrer.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2pwskvndt.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2hamnuxxh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2rnaxhseq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2hpbfbhsm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2vbofexqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2qslpzfkp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gt2rpwzbvhc.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2junjfqzr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gt2rrqzydjb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2srayxlnt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xilwrlzn.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2gsuwxloo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mifmeiar.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2cbzsiyqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2bopajfem.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdclujee.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2eycepcxv.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2jjvguwhj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gt2wzcddrqa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2spfzjjjq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2miptbhna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2dhgfsfer.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2agzfgmyq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2jpevfvyh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2cafcusba.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2fqdumoqj.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2yhojxdfh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gt2vqlnvxyw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2cnhugwdv.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2akzklbbb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2spazziwn.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2nnjxmsxj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2igjljbci.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2lxjskyhl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2enxkgbuz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2hekmemho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2yzzqceno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2vhzvrwzn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2hftimoam.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2evkcwusj.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2kgocfwbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gt2laqgwnfn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymnfajom.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2hpudgbwx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rqxhsprn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2qtfmojcp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gt2tltbohum.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2tlivbvkb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2xhxkxkuw.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohrmzqkk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gt2krhxfgeo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2khfgknft.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2wqylpqox.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2dymiknjn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2updjfvtb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2vajluars.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2luvdrgls.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2gowvkudg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gt2tarrqhtf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2wmxvyexu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2kvufyhuv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2jsrycfya.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2gigenqqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2tnmicgvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gt2zfvgwlqc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2xdxarobz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2fddfhrrl.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gt2bqtqiduk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2eumhtnxe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2qvgfpvac.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gt2zmnxtuii.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2edxmzbrd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gt2kurppxuv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejkpvati.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2bggbevqs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gt2kvsyqglv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2gmsktodz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2caepnpyp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2fdqfmucj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2jnmcgqcz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2uowomwha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2lgnjgabz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2hjpustnm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2avthbvry.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2zesboyws.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2veldgpfh.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2qlgcorax.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2lndbrouu.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2dxedziwu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2mcljscyv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2wmwkqhwu.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2bwswzxee.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2jifbixtc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gt2qbcjqmce.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gt2iuegjwun.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2ibjqzvat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppqjceuw.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gt2ejtmkhbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2mqtztyhc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2wkmactnz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2cmcfxhef.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgkzbzyd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gt2lmqejavu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2etnxuafx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2rhczwiyx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2xmrxamfu.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gt2xacvrcrg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2tpezurig.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhptgamr.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmtnfluz.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2byxnevvi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2nbhjpfmd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2qnafbksy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2fstpsiac.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2iooaiybm.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2tkksfcxz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2asxsiecf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2uhirqxzf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tusrfseq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2bsayoiio.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2zmjpqjdn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2oumjkatn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2supvugbf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2duvxbzzk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulmclmxk.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2plhfzhlb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hecyirgo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2tkhnrzaf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouppvxbt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ackasgqt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2wocphtco.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gt2lyefqkdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2qivjnmya.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gt2dwbrlgqf.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gt2ltfkjqhp.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2jmhnwvzh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2dcknfctn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2okbifsdp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gt2uversskl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2fecavtxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gt2fxndqhds.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2hsxqthdf.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2fcfdbddc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2kmiwdpok.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2vujtxwfn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2kabygdts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2resoisbw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2iuoptnee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqoradob.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2tosvgaej.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2uoyqbpqv.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2pfidyzez.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2riaogngt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2bujfhrmx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2speusawr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2mdagebtj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2hybbgaus.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2fropiksp.html


<!-- 参考信息 -->