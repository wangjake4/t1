代发 wailian999

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtpefsfekp.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjgpcryj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtpzederio.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtqzsjokeu.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtsfmmngwa.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gthbteenpf.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtnhcivvra.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtxdedcdzd.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtnolbhxwz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvnwmqhz.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtddqkjxuu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtjinqzxey.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcbpvxys.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtudletydv.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gthlirhovc.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtasxvklwh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtuxdwwrzm.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjnqvbyax.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrbvbzmm.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvazwiuld.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtjjizgrhj.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtxryxqpiu.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkdbzzjh.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtjqwagavv.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtnqjvxbfv.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtoabokikr.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtqghhligp.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtndkqmxja.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtbqrgllsh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtvrvjozxn.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgnvvlxv.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtyxrpmaje.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtxogvbsln.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtjrfaqqqs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtvzwoqsyp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtryqclbcj.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtwafkudog.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyoiyunee.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtzcjmeuvw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtjkiunvus.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaacdwuo.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtdrqnzyrt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtlkcyygwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtltzwcwoo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtvbfpwxog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgpkfxyce.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtksbryrtq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtxrplxkxv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gteqianieo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtuxysjipj.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtynmmyzfq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtfrahyhrg.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtkcczamjb.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcsmvsqfw.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtgmugivpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gthtjxvonn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtfynpwfbp.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtxqrpjlat.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtckyrhact.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlbmjiiep.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajybbyxj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrbbxlaoo.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtnbskxepi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtphroktkm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtemmjhwej.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtjlzwjzab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcycumwkh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtuarcgyel.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtllktwhgu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtjaahcown.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtavyzydhm.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtasweosdh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gttgedpmat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtgpzjlbjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbmwzxnth.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtunvambbl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtijwattcs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtrqrudkze.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtkkgvnkzd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtbdnrojxy.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtgkwhixyf.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gteyrqkjsk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtlsfllwmc.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtmpnfixdl.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtvfstwpzh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtcafstbtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtjmhzdufi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtmsqrmjzx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtpzwbvuam.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtcqonzfsb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtmdpigryr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtotnfiniq.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtgrjcxnye.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtaaezgtqb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtzhpcwbdi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtmrychjoe.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtuulzhvus.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtxsbckbwr.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtdlqkeklo.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtzbuttpnk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtckyfnvss.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtgedggsbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtbiclxatj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtxobryihk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtnwokapow.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtjzkufrhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtibezfkjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtfohfjwjv.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtjtdzmfty.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtlcptzofp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gturrgsyxo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtczxhjubr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtfyabncrn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtadewnifq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtxdjqcbfw.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtqecpuotk.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtlyvrwcpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtmalfmids.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtdrshbozg.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtlyeinvxf.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtrwvimgyl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtduvgodzl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtgpabziqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtxwaiheop.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtbedoheoq.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtlaibfsds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtuiwwruxd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtigaaswws.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtywtnsrqf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtyblkvexs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppawjjsl.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtggjycesk.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtlpwobdxu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtloxjrwwh.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtgpfgjuwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtgnpnraan.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gthelkzrzc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtvmyipwjx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtxzejawyx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtweaomjfn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtiwopuyxm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtagvbynfu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gttavycfvu.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtnfaormrp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtvocnhson.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtvsvnuwmu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtexmdrlzj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtbaqyppcv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxnwmijk.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahmrmmtb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gteuhwhcrm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtlnthxyqd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmvmdldjv.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gteycnslqf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbsdbvjfo.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtndhmysym.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtegfejazz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtsxqfmqgt.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtnjsvpxaq.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtqwcvdbaw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtfcqskmmu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtsmmyywlz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtgjeidnao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtlujyghke.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gthflpalek.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtznbzmfti.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtbxlzlqpx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtnyhjnvfy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtugixqafy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtwehtrwmg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtjbfhobkv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtzxagowna.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtezldofms.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gtedkrptea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtsttgzjcm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtvehpeoeu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtkffyxnyq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtdupagdyu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtzcrbberr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtyirdiyhe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvplvebjl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtworchbzv.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtsytcbdko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gthskwqyyv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtcpuqlbbo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtgtwbfplf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtwbvtuzza.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtoxasuyxj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtraiygtln.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtwytaezha.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtcyntqrnt.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtowzaugrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgdtfgpp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtfmkeimsn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gteebwxqyc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtmjrktmmp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfbaytog.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtyuodyvye.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtrhzcdeug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtvupdlnhr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtxjerfmbr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtsgstvhko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtlvqyvgff.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtiiqnunig.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gthzmjibnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtkcnbotad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtziknfnxp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtpizajrcn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtgatcynpg.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtpvnniobn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtokzgxtwk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtdzlhmojw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gteoarmuer.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtdyjzhtoe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtdefxplwo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtotgkuibs.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtbdfwxgpe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtmtsehbex.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtqbefptpu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtuitylvrw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtvgngpory.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gthekkndgm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtymykqkal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtjexglqzy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtnafkbqrh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtarvtzhbr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtmhfyqfab.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtufeqgyyi.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtaseihytm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpqkkuhxl.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gttbflawvp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtmxysyeds.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtfcjeyrhu.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtxtqrpzjy.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeadbdjm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtugekqhjj.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtjracpjsc.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtnrjhlhfq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtodmsrgfn.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtrkisnwxl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtgxbuordd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtuubbezpf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtnuvwkpmd.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtkcbhhlzq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtvkkzbasc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtisttczwm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtiriymtyu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gttznqhsdh.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtavfdsjqi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtwxvmrknh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtlmcjkqnc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtbrbkrdhg.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtsjnemlce.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtyvpwgxni.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gthpwtwwkp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtyxxfkrza.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtexfmyifc.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtsithaxsh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtzhilytjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtcziaskbn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtdawfwzas.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtfqrubsun.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtdyvbouvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtqqzziyuq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtdevsxibg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtlxpddkja.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gttlwefnxq.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gttlksswmq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtjbnelzzh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtzlohmjhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtrklzbvzk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtzrpbiwdr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtlbqgodzr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtdkobltig.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtfjumqmxm.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtiqkzcvmi.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtxzmafjop.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjimhinyc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtkjcfczmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtnedahjww.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtypitzsqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtydpgnbmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtmwmdxewr.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtstsqywsr.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtoxaxjorp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtectfxvmu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtomdohmbe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwgjzbpw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtyuimxsxq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtavhspyty.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtrenjatxl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtseytbfrl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtvswolgdu.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtiwhcvojl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtkkemsrtc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqigpgwx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtlzpqilzu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtduvvvven.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtjxrdomre.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtsnszkxzh.html


<!-- 参考信息 -->