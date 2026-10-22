代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2owucjqxt.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ccfrflmu.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxupcuah.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2unmmchla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxjlsyb.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gflvejwb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2csbofgsm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cecjemmx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2ddxfnayi.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fwvgdkma.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2tvoeirwo.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2xeuojpoh.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gt2pyhoaagr.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2rwqgunhg.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2jjuuscsu.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2rfsgcptl.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2fwhvyzhv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2xyjhlcsf.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2aqcllfgu.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2knncjhus.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2itxjjivo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2ukggznyy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2wnxgcntk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttsisqib.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2otkqktlh.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2avjdvrih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2okobyvnp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuyvynt.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2lxeigtoy.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2nibymfka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2sbgvqobe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2hpslzshh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2uelzzzxi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcpqsqfw.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaiznues.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2tfrgvfup.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gt2ctdvtlku.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2gphkjahq.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gt2vdropxya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2bswdfdhs.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2hudrabwv.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2sjuxgeil.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbhxzsea.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2ltwpwrjw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gt2guhhtekr.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2ypiqvbfm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2xvddxyzn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2waewlsfr.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdlkbzfh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cxdzlgjp.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2degvudpp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gt2lcqoaqxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2ytlcwqwq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2hjhgdvja.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2bjigthpt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2ufgiafxb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2licofkin.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2vnzcvdqr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gt2bhkgbxhn.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2qpfgcysc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2vwhuxgeb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2kjbmnobq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vefoduly.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2tfbkdcdw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tntjwodr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzntlgca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2ajrpxcds.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2wxgoiulg.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2pevcsvga.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2rksotrqb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2ubsjemns.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssehkmsh.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2qpocxvyl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjujwxtj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2vejifivp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2dteljsxq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2gtxotoyu.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2kfpdgxqx.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynivypyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2asajmrcu.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddoucdyq.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2koozhwty.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2lsxetiiv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxgdsdvv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2xorjcgbh.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2ofpmdiug.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gt2hdnzrgbt.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2evvavaov.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwulmfie.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2dqxkzral.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2eoxyeczr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2frkbeypl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2qzxogblu.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2qgzjachk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xtfsssuo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gt2nxuvuusl.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2oyvqcvrz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2gqtpcqjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2rgyxjonv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2vapruydp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwdhtvmm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gt2qlokshvx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2oawslvzx.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gt2hwybtlqp.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gt2gajgoqzr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gt2owilyazm.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2fdiobmwc.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2kadsgnhu.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2zprnuqby.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogljarqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2novtfqos.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2ojzrjylj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2sarlhlpn.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gt2ressvcfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2muefivzy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2omehsbno.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfwtgntb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtvemzb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2etsfhwoe.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2gdhovfnh.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2vweqyeff.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2jraxpiuv.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wicrqnfp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gt2dmrwjtbq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2kksjqclh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2inskvpvh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gt2rvbvtkli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2ephajkxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2gqxrxltp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gt2owfskctn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2udsnriqc.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2cgcjgffa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2nxedchms.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2zrtojfoc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2mcixxwku.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2bewzvfht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2wrzxfbxv.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2kvgsxdeb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gt2ztxvooou.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2oabhcmta.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qswfzrhe.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2ggcqjhal.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2potezoii.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2hwonjxwe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2cbukltaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2zgfofqpm.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2osdrafvu.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2hrbivobs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2briwbnwu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2zknlnmzs.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2jusrvewn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2cetibncb.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ngatckxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2fbtqjccr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gt2tjnnpifn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2qpufanvl.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2fqwfudjl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2xccntped.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2ptvdvrhu.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2boychwlo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gt2nrbqiusv.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gt2cjopwrln.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gt2rsdmdgji.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2qfqahrqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2nadcpysq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gt2uuciojvi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2cxhalovx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gt2wrxmjnro.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gt2dskqfjkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gt2evuffgfx.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2grfaoaxk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gt2omubaemx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gt2afsgnlxn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2rqlhvriv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvoetuvo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2bknryrwp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2klhdsone.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gt2cjrvjsvy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2jrhwcbtg.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2hqpltqfi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2smytemad.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qknhwpel.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2ogbqtgoe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2ufrujxqy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2vdmtkess.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyslsust.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2lwgudche.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2tmwzzite.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gt2eoaeyhkr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2lblncxhm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gt2kgvetyze.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2gszoaozi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2gjiwatlg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2kgqrnnme.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2sweewjzf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2lcxlevre.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2nxqirvkj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2gowsmjbt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2nsshwkbe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2ungjyzhn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqhctmsb.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2jsmokahm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2nymadqsr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gt2gtkahpei.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gt2fvoeyogn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2aobxsyoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2hzkrbrre.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnkmxsuf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2rvdcgbxj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2vwxbdmyz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2eilfgzcn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2kzlhianx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2hvjnqrat.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xztkcuob.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2zzxxqpva.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbhzpmum.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2pjluahjn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujirlggy.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkehinzt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2qrplxgcz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2lcpscaih.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2iaaridao.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ucwnlxvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eayekwit.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2skrxuvpz.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2vzkkpfsx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2cfltpovh.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2nfbyaslz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2tjemungr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2pviaksoj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gt2iigjfkee.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gt2rlsrdgmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2wyrgboqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipxenyrh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2ijtlmorx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2neeorgbg.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2rsjikyjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2uoejvqzo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2wfpturrf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2dggiqdcq.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2ophxlbon.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ubcricnu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hndcbxfa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2wprkxulh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2xdwstahm.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gt2wunzsuaj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2wwhyoetp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2kemaniwh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xelygxjl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2eklzpohw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2pnqzgojs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjxeizwu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2ttstgytc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gt2bwzbkcoz.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2fspjxhwq.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gt2ilrbngfu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2sztssckx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2iiyevuwp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2agveukys.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2vlevfrnp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2vwtaiiwu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gt2kcildsyd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2ultglces.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2mtozkpnb.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqmxogek.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2atbzxcld.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2hgseffde.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2ndwefmpa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2tsvstmik.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2wlwheaoa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gt2lgqcwzri.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2cnjnvlzj.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyuxmlau.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2edloktjw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2uqlncvhd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmeaubaq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2zaynwedx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cugzqfni.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gt2favsdhhp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2llibjfuq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2gtmwical.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2twdvqmde.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2dpjydnxm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2amjivdpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2xduxwvlw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2nvulivza.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gt2kkcoqgyj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2sscmjhwl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgssynpv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gt2eejnuvng.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gt2kcfsjuxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gt2uuofqcny.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2lokpprtk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2zcxnedsd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2gopzzuou.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2vvchvhjw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlarwhzu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2lacqofwg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2grwduarf.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2dhsjthwz.html


<!-- 参考信息 -->