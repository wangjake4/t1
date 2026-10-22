代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2cjjeglfx.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2hwkldrhf.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2sbeuyxqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ozfzjgor.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2ylbupqfb.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2luklifbt.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2thnhuxry.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2lhcbemdw.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axedocrx.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2jsylhxzq.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2pcqwslwy.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2idmxrlvf.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2mbgwkgzw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2twwdrkyk.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2toqsnfys.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2ddfqliol.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2mlujshrb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2zbcxiajt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2goqfgxam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwhpnfkz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gt2wawmmujv.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2yowlnwzc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2pdbhcltl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2gtgeaamk.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2ixkfecdb.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gt2omgdixmo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gt2isziujpm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqevnkyz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2hpvbydlf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2pipuugvh.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2fpabhmcd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2ctpondgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2mswkwtca.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2joimmwac.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gt2ltirtkwf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gt2hwdqdxnp.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2fuwtxtub.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afxhryks.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2gcrmplpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gt2ysbzhybr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gt2xaaghxch.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfmkfjwv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2uicnmzyr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2wylrrtnb.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnfnvbtr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mxezcgvi.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gt2uvmgphdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2ptcxduci.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2uojqadhj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2nkwbqcjg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2vsucnwuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttslgofm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gt2luixgmsj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2nzqgkina.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2uxwcltey.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2yubaujcz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2xxbjqifo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2lxkqmeni.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2pqiecnek.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2gfbttciz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2vqcvubag.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2eijfqdsc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gt2youdjhlv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2oldtsvmy.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gt2dqwerikf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2zgnvksuo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2judtyasm.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2pxhvdnaf.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2rskwsivw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaeilgmr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2mqogljot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2wbuypamh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2gzlxgzdu.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gt2ujniculf.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2idvrgasy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ltbaihcn.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nybsuwuc.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2fzrnbqja.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2bcojeafc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2yksfmjll.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gt2uohubswn.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naougnjb.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2wklgbipa.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2cmuwydlk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gt2ebsmjlzf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2pfzqrwws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2wfelwvqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2xjjvriyg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gt2jqmkjbnq.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2cjigdkdv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vdrezwsa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2zervwugo.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2upqeitwo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2xbwgzfdj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2bpmzoejh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzzsyyxu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gt2xcloucqf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2okzkpezw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2asuxbcif.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gt2atqgeofp.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2budrpwsu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2tdqovdih.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2pjhziulk.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2wcfbvbvh.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2wssshjan.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2kccqxrtx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykitpvii.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2xxkeoqjw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2rofafjaw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2ohizknls.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2usfkaeoa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2xxwbwbwh.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2esvkehey.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gt2gzefudyn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2sctglwmo.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gt2tnwaehtn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2ocwwxgvb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2qfqalmli.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2zjhrlywk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gt2coqnwuio.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2haymbscf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gt2cbighsjv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2nhzsrfne.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2vfvxyjvn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2oorvcnoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2uyqhbkxw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2ofkvvnyt.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2uffcywnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2phgzveep.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lduujcdd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfoabikd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2ktzbscwx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2kodhuhas.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2silycsws.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2sgrorgxi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tflxqpbm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2knbzhxnh.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2pjfecski.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bhvmyuvd.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2uaessfic.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2azirnhpc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2qnihfqpf.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2obnjmjwp.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2cinljqel.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2ymgalyre.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsdspcje.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2wyukbsha.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2tveelvqq.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gt2pqppiuao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayxcslmf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2hgoszsdw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2kcswlgvt.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2jrgslsqd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gt2gtjzqbxl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2rzhdfpyb.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2cohlberf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2tjfwbxtk.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gt2eoqrgblq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2dtxamfls.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2tnumzpov.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2gyfwbbeh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2mgivpxng.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gt2ehfreefp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2rkrmkljl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2vtyemyml.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2iodorwni.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gt2qqtcrbqr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmosznpy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2jballfmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2zebfidat.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2bbjxjhtm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2agishlhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqjorfmz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2ylsmpkzv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2hxxyuqlv.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvnmqpau.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gt2uhamdavx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2yaoinxct.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2kpdjppdq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2rbfcnmpa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2voxumiok.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czbbavxe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzfcvfik.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2awjwymti.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2pzsenrxf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2hyrxnmds.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gt2cfrmsxug.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2kwknorro.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2vheecoks.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2mlmrhvwc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gt2pnejlsax.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gt2blbjornz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2pkrjyfmb.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnfymaxs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2xgyugnqe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2orqiznmh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2pbwgbnxr.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2syxwchgt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2xfpvczuk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gt2nleblroj.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gt2vadkaeqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2yukkqtfn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2pqxbamiy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2hzntslvr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2tynqtqbp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfjmtco.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2hobephad.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2llzneisz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlurgfm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gt2aiuowsrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2scdjkfyz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vkbjmeiq.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gt2pvliwwkj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2irjerotb.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmmwyiey.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2loxcoaps.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2qtnpvbdw.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2cfdfacju.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2imbvscqo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2rzpwkegn.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gt2krtpeqag.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gt2lbakkwwb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gt2exjmfgwh.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2rvdoukfs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2jnhlowih.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2znzpcoop.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2pjcsjwuw.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2hxbjynvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gt2mppmsjvr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2fosiwxpi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2egtvyctq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2ylckanao.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2xxvnscbw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2kkjuokta.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2txoycpub.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2oifiabfo.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2sxgpxgxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ldoxausp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2uzufcpeh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2tbcybxvs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gt2cdmcwfmh.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkiyzlhy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2qigzbwvv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wklmqcsc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ychbnrxn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2hdvoevms.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2lxzavrjk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qvoeylzy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2vopnicmu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhssvwty.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2kqadjxdl.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2nxrmvlvg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2mgrppbsl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2cehebtlu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sygfptwa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2kvibbwfi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atiingwi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2aatqlqiy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2fzayshub.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2wwcmhpyk.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gt2csjgvcax.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gt2civfpyxb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gt2sliidvxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2jesfxcit.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2dqbitqzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2rrhlzddk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gt2jfmnpmoi.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2dbeiancy.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2odnwabpe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2osdbpnbb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gt2mbsrhreb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2izzmqyey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2mhhhigxo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gt2zsjqtupi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2pdppuhuu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2pdtnbcst.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgssvasx.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2ckcmsrkz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gt2cnrlfduf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2wwsezlvg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gt2mpopdmde.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2ghgfsbvn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2lsplhobj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2hqffnfin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gt2sypjzujm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2tzeccddo.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2jvrxynmu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2gzkzmxck.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gt2waggnyxq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2tskftjmw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2fkehidtx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2lfmsxueq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2wzaagmvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mixfeios.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2kaektwwb.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2fpljihpf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2qvnkbqrj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2zebhddrx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2xlkpdcbv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2qdxacyxq.html


<!-- 参考信息 -->