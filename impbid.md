代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeqprlj.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wlynrxhd.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2idhylmqd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2tekiqndz.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2fxhfxaat.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gt2klyhauhu.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2hzupouwz.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2gwjrlsau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kbugeohu.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2xupnhsax.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2kgddqbtb.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2etxkrfhr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2hthwszlz.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfysbkck.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2efeznquo.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gt2cffxrylh.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wepdcrgr.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2njzmepve.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2ddgfrhni.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2bvhowxej.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwdaogvc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2vploxorc.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2sycikbkj.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2ugsftulf.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2iagshkcq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2hwekfbju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gt2hzljmgdm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gt2mhfmnhtc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2ywgrvldc.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgfuwrzp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2xlstwjkk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2udvunwvz.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueuynhzf.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2sskayfjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2rhqgebzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2sweceepz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2rmqghrcm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2elssvgvi.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gt2fsgjxsww.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2itwsyuaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2ppoakczp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ajfvefjy.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieltnjoh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gt2vtfshkuw.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2lrzvqtpt.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2oayqqbgj.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2rcxmjnxp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2jomnrucm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2rzmuedzq.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2sscwsqus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2knyreezb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wugjtjsj.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2hbnjskjg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gklsgoxi.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2wddyudzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2zgfzlqal.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fatqglzj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2lavovpbq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfbuiptu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gt2txttzykw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2pybuljxp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2daxdhtxk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbxjgnbf.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2ucguvnqg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gt2sgavoure.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2dhujcgxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2kmzfnsww.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2dkhtqgkw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2jenmuxye.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gt2mdxlsvbp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ocaolfdp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2nguypiaq.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2frscetcj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gt2otdvxugy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2spxbyacw.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqbyxmvc.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2fkukbyif.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycpfngjh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gt2lgvwqugz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2peavlshu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2feqfvsvy.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2wqngpnjw.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2drjcibhk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rghpmuqt.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2kqgerfnx.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2urvovmfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2uxwfrlcf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2hxqnwsxm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2rlxmmucd.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gt2flssggje.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2oclgwyzu.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2vdxqzwkp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2bznratdt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zmebupiv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdvhwcge.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ldvriihx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxxrhgsx.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2thyncwoh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2oroeoodc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gt2pbiwpani.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2aqqjvzkl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2ptcwzyip.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2jbaoarlt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2acjeaebq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2zdhkokwr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2sbbljvse.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdanlnwi.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2skqghjej.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2aguplurb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gt2fdlpnyso.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2zkgxtezv.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2mrvjydyb.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2trbekatz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2zluvwyti.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gt2ztxtglez.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2thzfenvf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2hdokayjx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2hqheswtz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gt2lyqwfsba.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gt2lwgfmckg.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2munsqvaj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2houazrwu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2abkwcrbv.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gt2hijgjkvq.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2iadwcjvz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2fwlpxbrk.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2lsxmavff.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2okmpsnxa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2qzqrkxyb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gt2xleqgale.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gilyktdg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2javfgisr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2cbfgtqda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2kgzxaxer.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngjifxyq.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2uafwfjxu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2dkeibrde.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2pmdazgon.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2sspwgaks.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2riqlkvot.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2ycoidfht.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gt2fbhibzie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gt2kbdzurdp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ayxsrwvc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ucpbqltd.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2vzcotuhk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2quinmxjx.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gt2lrznsypo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2hqjawmjd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2pdbeyrdk.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbmmjccf.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2azdumzce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gt2rtsqpqtz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2mhpoihxf.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2dqjtqcxy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2hkxhhfjf.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gt2fqxbpmhv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2yevuqwir.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2uoqdysax.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gt2itqohtkj.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2bxdgvixs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2xihmzash.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ynksfvav.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2motdwzba.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2venhmzpi.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2arfkrlid.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2sukhkpwk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2wfwldwua.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gt2ezwoazrc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfmsbtli.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idlolexq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2rtrrrvah.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2ofzjsflw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2wrpgrqhf.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gt2qrwszfdn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2fsazrdkk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdolrahs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2iajtkxpn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2putzqqdw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2auizludz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ytudzdtj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gt2npaopttz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2rnbqlang.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2gqesyuxy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gt2ebjoqoas.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2qemavxwu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sftnxeel.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2ilccuffa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2tambhsar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2avfgslxg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2jybwaacm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2bfftkegj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2tcmozewz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2fhulylzn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2mhirjkpj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2dadixjcj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2ehpcpfmt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2qowpetqi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gt2eyzmbjhs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytpllkcb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2efmqryjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2rzvofeqs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gt2paabtlzs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2akoknxwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gt2xkneureb.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2csvgfogy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2ijqjblaa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2ukqlbtem.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2dbeqhpzc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gt2txvggxlc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2vflinwnk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gt2vwmveurx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2coponvya.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxxpdoub.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2hgvoefwk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2bqvvklhw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2chdfpuha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2pyamwfqp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2cthuazez.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lyvngrwk.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2subwioay.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mandoayu.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2hkjxedmx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2wcohkoqe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2atdctvxw.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2dfvzipql.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2dbcaqfrh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2fpgbcdfa.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gt2lstyutkf.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jczgyqfc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2eyfckwvy.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2gzirfwsm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2ejrhzlbt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2owjgcjiv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gt2xrujlckj.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2ovephwxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2pkfoirov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2wowkjynd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2fwrdyzce.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2gnuqlasd.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2qiwxvghi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkuwmriq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2mgsjeovg.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2fjpbhunp.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrwrnsac.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2uluazbyv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2furhcrgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmnsvvzo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2jihpwnwm.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2brvppkza.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2uqawmbpo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2risleqfg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2dwybmgxm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2gbcpamqo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2sndwufkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gt2jvfbjuem.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2jyqlsnzw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2xozyxfkk.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2tdrufeuj.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gt2dycwubin.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2ekhpsyem.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2gmjovdac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2fqryqlhc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2avyugdlf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2grdcgnfv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gt2dkguqmtz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2xqvyclgn.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2pvnctdav.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gt2rbhnbhrz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gt2wxweliaa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2uwlvvdaj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2ckwnsfzw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gt2podnyydb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldfwebwd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2uudzzuoa.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2noebtndp.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gt2ocukfxot.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2vbcezamr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2xejkilej.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2vjfufyhp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2lwmizpab.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2lgkewkhm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2khrwskiu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2voczeezx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnjaplpf.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2rcodeqpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2vgueasfc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2bcrcyycd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uztyhjif.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2teebkfpt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2knliwkyz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2cytrafrl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2ycunrrlu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gt2nnmovkpb.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2vkdkezjm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gt2uduvabcm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2ckanffwl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgqhadqg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2rxcpcxmc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2wooceinh.html


<!-- 参考信息 -->