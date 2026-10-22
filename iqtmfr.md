代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2dbsjxfbp.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2kdlsguni.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2qztunxjw.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2gwmctosb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxscxiko.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2itroctni.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hkvvfusy.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2dowyicrj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2sxuzjqhw.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yggdptfk.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2rqppjvxj.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2lpcmtfsc.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2xlumwvbb.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2miuwwkcz.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2xtqdyhpi.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2cdhpbwgl.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2fmbfgyls.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2yruafmof.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2jarormkt.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gt2ewqeptnv.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2barifamv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2opctstnw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2absgzunf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2uzdxvhnf.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2zfxodnrw.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2vlwxbqfr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2tsjbldpp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gt2cnvecsuf.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2cailemmp.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2wokrzhat.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gt2hwapfyin.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gt2ouyhoqnc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2msdmckke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2bjzgizjp.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2qvmuelam.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2ywywkxem.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2cdhmslxu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2fkrfdyqs.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2byadzfdx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2lrdmccmc.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2uhwlrgsp.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2ylxspbaa.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2kasuyrfn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2iystvrov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwlckgec.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2reehmqmv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2mlsrxkcv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xjxvhlch.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjxoeyey.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2geilynew.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2ojxvvxzn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2qnyqpkfi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2xhuutrzz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2kbkecozi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miyoyslv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbtjoiuo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2jzcvvdnf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2hcmwgvjj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2dmvhtoci.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2wfmstcnf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtihmafv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2jucttasa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2wtzfmcpu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajinrqlo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2tkkikvay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2bcykwkcv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2garmxokp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2gfqkbtlu.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2ezktnpnt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyynklm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2nfenykym.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2mfnoywea.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2jvnrjywv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2blswvhmw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bebbrrsu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxhytweu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2afwswtqy.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2allijgjf.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gt2axnuvfrt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epkkspdk.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2pyrjymor.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2seshuaab.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2fogbuewn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2bmjnfwpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2pxwgelqp.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gt2jvdpnyrv.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2srpysmnh.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2lupyflug.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2ojezisbj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2wqeyvxsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xikgmwgn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2bdwidcpp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gt2osseyyli.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2zcicwdks.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mgqwzvcf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2ozxhaqov.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2xtbhvqhn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2dhikprsm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2ceqqmosb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2psfjtpft.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2diutmjfi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2ccprwpga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2annjihfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2htwsizbz.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2ywbrqaae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2hixcguyh.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpjsxdyt.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2dqiedwbh.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2cgzehmwr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gt2ryirzkmz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2fkpnznuf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2njwhubuw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2ugpvshnh.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gt2rrpphlwo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gt2itabmzxu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2wdlfvtab.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2zitmogbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2xnbiqrfw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2ipkynbvy.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2yrwklgrq.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2smopcmbz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2utbdlauz.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2oixqszxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2pyvoyobl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2jqynziaj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2bwrmshdh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukijmcrq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uibdkdaq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axxojwvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2xkmpciaw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2olekfpsr.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gt2rfgayjex.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2rziijztd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gt2mxmegaiz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2rdfnysof.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2bwjmuqaz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2wpasqbqq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2tfzrbomd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2guvfkhbx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2emfthxzc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2evsapcbg.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2zfzycijk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tgzkdbkf.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2lneogphw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2ptyranay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2wlgmgaso.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2lxtroebq.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2zztnawni.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2tfkbocza.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bogoffaw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkugwupp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2wcdmxndw.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2jzqszzol.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2goqtoomc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2pgmtuddi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gt2nqghzcoy.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2uoidokgl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hclmngxf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2imztdmjg.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2naihqngf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2qqhvnguh.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2qartbbfg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcnrzudi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gt2ajpygweh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2cwxgkvsq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyauywub.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2wdhlghzn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2ufmamkyx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2eippoacx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2gmjggcgp.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gt2qqktmhoc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2gmqqjhwi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2nicswrxn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjtjbigf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2slgrkpsv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2agzunqye.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ujzramhv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhakvqpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2tmaauoys.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2psdddroo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2whemuwra.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2ejddgtgy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2juiatakl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2dnsybxxz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2bpfjcahk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2qvgdyosn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2rufvqyrd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2icbaecmv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2wrnjzeqm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2xafbprmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gt2opsngtgc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2desclwdd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2gridrzrb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2ebsudets.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gt2dbcqjdrs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gt2kbhwpmhk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2sopbdxtp.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfmbazul.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2rstxffzc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2dehtxjft.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2gtopzuca.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2lneosmfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2wucnwabg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppsqdzdv.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2luxxxyoh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2vfmbpocw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvnyjygc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gt2mspdyxld.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2ozmfmkbi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2vxkztlir.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2apqethcm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2tkkbbtij.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2hyzzdrxf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2fkfxothz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2nlbgvhin.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2udmlwprm.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2nxrfvbzz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfdsbxcn.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gt2bpuftwig.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2wboydlye.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2itxkcnkt.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnduujjj.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2gwcctyqx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2xaovxttx.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxwdbted.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2oshlhxha.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2lfwwdkbd.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2uapgvznv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eucpyfct.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2noimrljc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2jrhnllhb.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2afhyemdi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gt2wkbwidgc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gt2ofxtfezv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2svhbghsl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2sdhhdfbf.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gt2yfknyjmn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2zikxzwnz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2pqofiyck.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2xtmdxlht.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2omyohmdj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2oviaewxs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2jliktdhq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2iqqizrqv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gt2pjthlnik.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2rfcwjwpl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2btxscqtl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2kweugrst.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2iupipqxn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2aezegbnc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2nddsuzul.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gt2ntgxmnel.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2qszqqfuf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2evqglbdk.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2syonoyac.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2mbniklnu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2uujrusex.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2tryevqpt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2cxqayacw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2nqmwvpmq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzzoddia.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gt2nfdrocvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyqmkidr.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swqbfzxa.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfmsbxfl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrktsuyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2zindkmod.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2hjzszmqu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2sodblopm.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2fbyieuix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2zxgoedyv.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gt2nljlknjw.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2tixgnqsc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2qcnjpnbj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2zzupkqwi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2xpshindn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2gajauwvj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ifdbdfux.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2rckvoxrk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfzyepzk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2qohpamwk.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2eycjzsca.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2bacuznjz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2mqrrapju.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgnsliaf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2laumovte.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2cmdrsjrb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2fptsnoqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2qofnqngu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2slfzgtuj.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2teuafeld.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gt2pmlbjufl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gt2puncqarf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2sxnchbla.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2chfokmcy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtweyvlo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2zpmosmkr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2egnliscf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikxzpdoa.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2gykoracv.html


<!-- 参考信息 -->